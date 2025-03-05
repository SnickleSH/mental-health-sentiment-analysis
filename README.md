# mental-health-sentiment-analysis

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

A machine learning project designed to analyze and predict mental health conditions based on sentiment analysis of textual data.

**Dataset**: [Sentiment Analysis for Mental Health](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health/data)

---

## 📌 Project Overview

The **Mental Health Sentiment Analysis** project aims to develop models that classify mental health conditions using natural language processing (NLP) techniques. The dataset includes statements labeled with different mental health statuses, such as depression, anxiety, stress, and suicidal tendencies. The insights derived from this project can support mental health research, sentiment analysis, and chatbot development.

---

## 📂 Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         mental-health-sentiment-analysis and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── mental-health-sentiment-analysis   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes mental-health-sentiment-analysis a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------


---

## 📊 Dataset Details

The dataset is a carefully curated collection of mental health statements labeled with different mental health statuses. The raw data has been cleaned and structured, making it a valuable resource for NLP-based mental health analysis.

### **Data Sources**
The dataset integrates information from multiple Kaggle datasets, including:

- 3k Conversations Dataset for Chatbot  
- Depression Reddit Cleaned  
- Human Stress Prediction  
- Predicting Anxiety in Mental Health Data  
- Mental Health Dataset Bipolar  
- Reddit Mental Health Data  
- Students Anxiety and Depression Dataset  
- Suicidal Mental Health Dataset  
- Suicidal Tweet Detection Dataset  

### **Data Structure**
Each entry in the dataset contains:

- `unique_id` - Unique identifier for each statement  
- `Statement` - The text expressing a mental health condition  
- `Mental Health Status` - One of the following labels:  
  - Normal  
  - Depression  
  - Suicidal  
  - Anxiety  
  - Stress  
  - Bi-Polar  
  - Personality Disorder  