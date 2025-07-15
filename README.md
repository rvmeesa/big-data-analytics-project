# Marketing Data Analytics Pipeline with PySpark & Gradio

## Overview

This project analyzes textual data scraped from a marketing blog ([https://blog.coupler.io/marketing-data-analytics/](https://blog.coupler.io/marketing-data-analytics/)) using PySpark, machine learning, and a Gradio interface. It includes data ingestion, preprocessing, statistical analysis, clustering, classification, topic modeling, deep learning, reinforcement learning, and visualizations—showcasing big data techniques.

---

## Project Structure

- **Fa21_Bds_024(Bda-Project).ipynb**: Jupyter notebook with the complete analytics pipeline.  
- **README.md**: This file.  
- **data/marketing_data.csv** *(optional)*: Generated during execution.

---

## Features

### 🔹 Data Ingestion
- Scrapes headlines using **BeautifulSoup**.

### 🔹 Preprocessing
- Cleans and tokenizes text data.

### 🔹 Statistical Analysis
- Computes word frequency variance and content length correlation.

### 🔹 Machine Learning
Implements a variety of algorithms:
- **K-Means Clustering**
- **Linear Regression**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **DBSCAN (Density-Based Clustering)**
- **LDA (Latent Dirichlet Allocation for Topic Modeling)**
- **Deep Learning (TensorFlow-based Neural Network)**

### 🔹 Reinforcement Learning
- Implements **Q-learning** on the **CartPole-v1** environment (from OpenAI Gym).  
  *(This is a standalone module not connected to the main text pipeline.)*

### 🔹 Visualization
- Word frequency bar charts
- Cluster plots (e.g., 2D embeddings)
- Q-learning Q-table heatmaps

### 🔹 Gradio Interface
- Provides an intuitive **web-based UI** to interactively run and visualize parts of the pipeline.

---

## Prerequisites

- **Python**: Version 3.8 or later
- **Java**: Version 8 (required for PySpark)

---

## Installation

1. Clone the repository or download the files.
2. Install all required Python packages using:

```bash
pip install -r requirements.txt


Prerequisites

Python 3.8+
Java 8 (for PySpark)
Dependencies: pyspark==3.5.4, findspark==2.0.1, requests, beautifulsoup4, pandas, numpy, scikit-learn, tensorflow, gym, gradio, matplotlib, seaborn

Install dependencies:
pip install -r requirements.txt

Open Fa21_Bds_024(Bda-Project).ipynb in Jupyter Notebook or Google Colab.
Run cells to execute the pipeline and launch the Gradio interface.
```
## Usage

- Ingest Data: Scrape headlines via the Gradio interface.
- Preprocess: Clean and tokenize text.
- Analyze: Run statistical analysis, machine learning, or topic modeling.
- Visualize: Generate plots for word frequencies and clusters.
Note: Reinforcement learning is separate, using CartPole-v1.

## Notes

The dataset (headlines) is small, limiting some model performance.
URL in Gradio (https://blog.coupler.io/marketing-data-analytics/) differs from initial scraping (https://blog.hubspot.com/marketing).
DBSCAN may need parameter tuning for better clustering.


