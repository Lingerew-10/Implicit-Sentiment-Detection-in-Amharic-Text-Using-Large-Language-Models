Implicit Sentiment Detection in Amharic Text Using Large Language Models

Overview

This repository supports research on implicit sentiment detection in Amharic text using large language models (LLMs). The project focuses on identifying sentiment expressed indirectly through context, word choice, and implied meaning rather than through explicit positive or negative sentiment words.

Amharic is a widely spoken Ethiopian language, but computational resources for advanced natural language processing remain limited compared with those available for many high-resource languages. This project aims to contribute resources and experimental methods for Amharic sentiment analysis.

Research Objectives

The objectives of this project are to:

Investigate methods for detecting implicit sentiment in Amharic text.

Develop and evaluate machine learning and large language model approaches for Amharic sentiment analysis.

Prepare a labeled Amharic dataset for model training, validation, and testing.

Analyze model performance using appropriate evaluation metrics.

Support further research on low-resource Amharic natural language processing.

Dataset

The dataset is intended for implicit sentiment detection in Amharic sentences.

Dataset details

Language: Amharic

Task: Implicit sentiment detection

Data format: CSV

Annotation: Sentence-level sentiment labels

Intended use: Model training, validation, testing, and evaluation

The final dataset size, class distribution, annotation procedure, and data-splitting strategy will be documented after verification.

Dataset Format

The dataset is expected to use the following columns:

Column

Description

id

Unique identifier for each sentence

text

Amharic sentence

label

Sentiment category assigned to the sentence

label_id

Numeric representation of the sentiment category

Example structure:

id,text,label,label_id
1,"የምር በጣም ጥሩ ነው።",Positive,2
2,"እንደጠበቅኩት አልሆነም።",Negative,0

These sentences are illustrative examples, not verified entries from the research dataset.

Repository Structure

Implicit-Sentiment-Detection-in-Amharic-Text-Using-Large-Language-Models/
├── README.md
├── data/
│   ├── train.csv
│   ├── validation.csv
│   └── test.csv
├── notebooks/
│   └── model_training.ipynb
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   └── evaluate.py
├── requirements.txt
└── .gitignore

This is a proposed structure. Add only the files and directories that actually exist in the repository.

Methodology

The planned research workflow includes:

Amharic text collection and dataset preparation.

Text cleaning and preprocessing, where appropriate.

Dataset labeling and quality checking.

Separation of data into training, validation, and testing sets.

Fine-tuning or evaluating suitable language models.

Model evaluation using accuracy, precision, recall, and F1-score.

Error analysis and discussion of limitations.

The specific models, experimental settings, and evaluation results will be reported after the experiments have been completed and verified.

Reproducibility

Model names, software dependencies, random seeds, training configurations, data splits, and evaluation procedures should be documented to support reproducibility.

Installation instructions and executable training scripts will be added when the implementation is available.

Ethical Considerations and Data Use

The dataset should be shared only when its source, consent requirements, privacy implications, and applicable usage permissions have been reviewed. Any restrictions on redistribution should be stated clearly.

Research Status

This repository is intended to support the development and evaluation of methods for implicit sentiment detection in Amharic text. Dataset statistics, model configurations, and quantitative results will be updated as verified research outputs become available.

Citation

If you use this dataset or code in your research, please cite the associated research publication when one becomes available. Full citation information will be added here.

Contact

Research area: Amharic Natural Language Processing, Sentiment Analysis, and Large Language Models.

Please use the GitHub repository's Issues section for questions, reproducibility concerns, or suggestions.
