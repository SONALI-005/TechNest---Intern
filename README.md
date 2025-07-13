# TechNest---Intern
This repository contains four independent data science mini projects that demonstrate practical skills in machine learning, deep learning, optimization, and data engineering. Each project addresses a specific objective using real-world datasets.

---

## Project 1: Fake News Detection using Deep Learning

**Objective**: Develop an LSTM-based model to classify news articles as Fake or Real.

**Tech Stack**:
- TensorFlow/Keras
- Natural Language Processing (NLP)
- NLTK
- Scikit-learn
- Matplotlib

**Key Highlights**:
- Preprocessing: Tokenization, padding, label encoding
- Model architecture: Embedding → LSTM → Dense
- Evaluation: Confusion matrix, classification report
- Training metrics visualization

---

## Project 2: Supply Chain Cost Optimization

**Objective**: Formulate and solve a cost minimization problem using linear programming.

**Tech Stack**:
- PuLP
- Pandas
- Matplotlib

**Key Highlights**:
- Modeled transportation problem with supply, demand, and costs
- Solved using LP solver from PuLP
- Visualized optimal transportation plan and minimized total cost

---

## Project 3: Exploratory Data Analysis on Netflix Shows

**Objective**: Conduct EDA to identify patterns, trends, and content distribution on Netflix.

**Tech Stack**:
- Pandas
- Seaborn
- Matplotlib
- Plotly
- WordCloud

**Key Highlights**:
- Analyzed content by year, country, type, and genre
- Visualized temporal and categorical distributions
- Identified content production trends and top genres

---

## Project 4: Titanic Dataset – Automated ETL Pipeline

**Objective**: Build a reproducible ETL pipeline for Titanic dataset preprocessing.

**Tech Stack**:
- Pandas
- Scikit-learn
- ColumnTransformer
- Pipeline

**Key Highlights**:
- Handled missing values and categorical encoding
- Engineered features such as Title and FamilySize
- Modularized steps using scikit-learn’s Pipeline and ColumnTransformer
- Output: Clean dataset ready for model training

---

## Repository Structure

```plaintext
project_1_fake_news_detection/
project_2_supply_chain_optimization/
project_3_netflix_eda/
project_4_titanic_etl_pipeline/
