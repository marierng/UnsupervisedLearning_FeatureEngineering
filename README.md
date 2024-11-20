##Mental Health in Tech Workplaces - Unsupervised Learning and Feature Engineering
This project analyzes the 2016 Open Sourcing Mental Illness (OSMI) survey data to understand mental health concerns in technology-related jobs. By applying unsupervised learning techniques and feature engineering, the analysis identifies actionable insights for Human Resources (HR) to address mental health challenges in the workplace.

#Project Overview
The tech industry is known for high demands, which can lead to mental health challenges. This project aims to:

#Explore and preprocess the OSMI dataset.
Reduce data complexity for better interpretability.
Apply clustering algorithms to categorize individuals based on mental health-related responses.
Provide insights and visualizations for HR departments to enhance workplace mental health strategies.
Key methods include:

#Data cleaning and preprocessing.
Dimensionality reduction using MCA (Multiple Correspondence Analysis).
Clustering with K-Means and visualization with t-SNE.
Profiling clusters to identify patterns and trends.
Features
Data Cleaning: Handles missing values, standardizes inputs, and processes demographic data like age and gender.
Dimensionality Reduction: Uses MCA to reduce high-dimensional categorical data.
Clustering: Identifies groups based on survey responses.
Visualization: Provides bar plots, pie charts, and t-SNE visualizations of clusters.
Cluster Profiling: Summarizes key characteristics of identified clusters to assist decision-making.
Dataset
The dataset is sourced from the OSMI Mental Health in Tech Survey 2016. It includes responses on:

#Workplace environment.
Attitudes toward mental health.
Demographics.
Accessibility and effectiveness of mental health resources.

#Challenges:
High dimensionality with 63 features.
Missing values.
Non-standardized categorical responses.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/marierng/UnsupervisedLearning_FeatureEngineering.git
cd UnsupervisedLearning_FeatureEngineering
Install required Python packages:

bash
Copy code
pip install -r requirements.txt
Usage
Run the mentalhealth.py script to preprocess the dataset, apply clustering, and generate visualizations:

bash
Copy code
python mentalhealth.py
Ensure the dataset (mental-heath-in-tech-2016_20161114.csv) is in the same directory as the script.

#Results
The analysis identified four clusters with varying levels of mental health risk:

High-Risk Group: Limited resources and accessibility to mental health support.
Moderate-Risk Group: Adequate access but lack of proactive discussions.
Low-Risk Group: Some resource access, but less frequent discussions.
Ambivalent Group: Minimal support and accessibility.

#Visualizations include:
Gender and country distribution.
Correlation heatmaps to identify redundant features.
Cluster representation in reduced dimensions using t-SNE.

#Limitations and Future Work
The dataset may not fully represent all tech industry demographics.
Responses may be subject to self-reporting biases.
Future enhancements could involve integrating other datasets or testing advanced clustering algorithms.
