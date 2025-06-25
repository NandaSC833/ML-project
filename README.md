## ML project
## notebook/

1. EDA STUDENT PERFORMANCE.ipynb: Exploratory Data Analysis on student performance (math, reading, writing) covering data checks, stats, distribution, and insights like performance by gender or test prep

2. MODEL TRAINING.ipynb: Likely covers training regression/classification models (massive, but not previewed).

## src/:
Source code — contains pipeline modules for preprocessing, model training, evaluation.

## app.py + templates/: 
Web app interface (likely Flask) for serving predictions.

## .ebextensions/, artifacts/, catboost_info/: 
Config, model artifacts, and CatBoost booster metadata typical for AWS Elastic Beanstalk deployment.

## setup.py, requirements.txt: 
Package setup and environment dependencies.

## CI/CD workflows in 
.github/workflows — project includes automated tests/deployment pipelines.

## 🧩 Project Highlights
##Data Analysis & Feature Engineering

-Extensive EDA on the Student Performance dataset (~1,000 rows, 8 columns), including data cleaning, stats, categorical vs numeric features, and new features like total and average scores 

## Pipeline Architecture

-Modular code in src, encapsulating data processing and modeling steps.

-Likely supports scalable and reproducible training workflows.

## Model Training & Artifacts

-Uses CatBoost (and possibly other ML models).

-Trained artifacts, preprocessor objects, and logs are stored under artifacts/.

## Web Deployment

-app.py combined with templates/ indicates a user-facing model inference UI.

-AWS-ready (Elastic Beanstalk) with .ebextensions customization.

## CI/CD & Packaging

Packaged via setup.py for easy installation (pip install -e .).

Includes GitHub Actions workflows to automate testing and/or deployment.

