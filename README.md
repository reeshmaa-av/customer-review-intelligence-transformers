# customer-review-intelligence-transformers
Built an end-to-end NLP pipeline using Transformers, BERTopic, Spark NLP, and machine learning to uncover customer insights, identify hidden themes, and generate predictive business intelligence from review data.

# Customer Review Intelligence using Transformers & Topic Modeling

## Project Overview

This project builds an end-to-end Natural Language Processing (NLP) pipeline to analyze customer review data and uncover meaningful insights using modern Transformer-based techniques.

The workflow combines Spark NLP, Hugging Face embeddings, BERTopic, clustering, dimensionality reduction, and machine learning to convert unstructured text into interpretable business intelligence.

The project demonstrates how NLP and machine learning can be integrated to identify hidden customer themes and support data-driven decision making.

---

## Business Problem

Organizations receive thousands of customer reviews but extracting actionable insights manually is difficult.

This project addresses that challenge by:

- Processing large-scale textual review data
- Identifying hidden discussion topics
- Understanding customer behavior patterns
- Converting text into predictive business features

---

## Project Objectives

 Perform large-scale text preprocessing  
 Generate contextual text embeddings using Transformers  
 Discover customer topics using BERTopic  
 Visualize topic patterns and relationships  
 Build predictive models using extracted features  

---

## Tech Stack

### Programming
- Python

### Data Processing
- PySpark
- Pandas
- NumPy

### NLP & Deep Learning
- Spark NLP
- Hugging Face Transformers
- Sentence Transformers
- BERTopic

### Machine Learning
- Random Forest
- Logistic Regression

### Topic Modeling Components
- UMAP
- HDBSCAN
- CountVectorizer
- c-TF-IDF

### Visualization
- Matplotlib
- Plotly

---

## Architecture

Raw Review Data  
↓  
Data Cleaning & Preprocessing  
↓  
Transformer Embedding Generation  
↓  
BERTopic Topic Extraction  
↓  
Topic Visualization  
↓  
Feature Engineering  
↓  
Predictive Modeling  

---

## Project Workflow

### 1. Data Preparation
- Load review dataset
- Handle null values
- Prepare text for analysis

### 2. NLP Processing
- Tokenization
- Text normalization
- Dataset conversion

### 3. Transformer Embeddings
Generate contextual embeddings using:

```python
sentence-transformers/distilbert-base-nli-mean-tokens
```

### 4. Topic Modeling
Build topic extraction pipeline using:

- BERTopic
- UMAP
- HDBSCAN
- CountVectorizer
- c-TF-IDF

### 5. Topic Discovery
Extract:
- Topic clusters
- Topic frequencies
- Keyword representations

### 6. Machine Learning
Use generated topic features to train:

- Random Forest Classifier

Evaluate:
- Accuracy
- Precision
- Recall
- F1 Score

---

## Key Outcomes

- Converted raw customer reviews into structured insights
- Extracted interpretable customer discussion topics
- Built predictive models from discovered themes
- Demonstrated practical applications of NLP in business analytics

---

---

## Installation

Clone repository:

```bash
git clone https://github.com/yourusername/customer-review-intelligence-transformers.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Fine-tune Transformer models
- Add sentiment analysis
- Deploy interactive dashboard
- Optimize topic coherence
- Build real-time inference pipeline

---

## Skills Demonstrated

Python • NLP • Transformers • BERTopic • Spark NLP • Machine Learning • Topic Modeling • Data Visualization • Business Analytics

---

## Author

**Reeshmaa Anitha Venkatachalam**  
Business Analytics Graduate | Data Analytics | SQL | Python | Tableau | Power BI
