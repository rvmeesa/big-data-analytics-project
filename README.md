Overview
This project analyzes textual data scraped from a marketing blog (https://blog.coupler.io/marketing-data-analytics/) using PySpark, machine learning, and a Gradio interface. It includes data ingestion, preprocessing, statistical analysis, clustering, classification, topic modeling, deep learning, reinforcement learning, and visualizations, showcasing big data techniques.

Project Structure

Fa21_Bds_024(Bda-Project).ipynb: Jupyter notebook with the complete analytics pipeline.
EADME.md: This file.
data/marketing_data.csv (optional): Generated during execution.

Features

Data Ingestion: Scrapes headlines using BeautifulSoup.
Preprocessing: Cleans and tokenizes text.
Statistical Analysis: Computes word frequency variance and content length correlation.
Machine Learning: Includes K-Means, Linear Regression, SVM, Logistic Regression, DBSCAN, LDA, and deep learning.
Reinforcement Learning: Q-learning on CartPole-v1 (standalone).
Visualization: Plots for word frequencies, clusters, and Q-table.
Gradio Interface: Interactive web interface for running the pipeline.

Prerequisites

Python 3.8+
Java 8 (for PySpark)
Dependencies: pyspark==3.5.4, findspark==2.0.1, requests, beautifulsoup4, pandas, numpy, scikit-learn, tensorflow, gym, gradio, matplotlib, seaborn

Install dependencies:
pip install -r requirements.txt

Open Fa21_Bds_024(Bda-Project).ipynb in Jupyter Notebook or Google Colab.
Run cells to execute the pipeline and launch the Gradio interface.

Usage

Ingest Data: Scrape headlines via the Gradio interface.
Preprocess: Clean and tokenize text.
Analyze: Run statistical analysis, machine learning, or topic modeling.
Visualize: Generate plots for word frequencies and clusters.
Note: Reinforcement learning is separate, using CartPole-v1.

Notes

The dataset (headlines) is small, limiting some model performance.
URL in Gradio (https://blog.coupler.io/marketing-data-analytics/) differs from initial scraping (https://blog.hubspot.com/marketing).
DBSCAN may need parameter tuning for better clustering.


