# Mental Health in Tech Workplaces - Unsupervised Learning & Feature Engineering

## Overview
This project analyzes the **OSMI Mental Health in Tech Survey 2016** to identify mental health patterns and provide actionable insights for HR departments. Using **unsupervised learning** techniques and feature engineering, it categorizes employees into distinct risk groups and visualizes trends to guide workplace interventions.

---

## Features
- **Data Cleaning**: Missing values are handled, demographic data is standardized, and responses are categorized.
- **Dimensionality Reduction**: MCA (Multiple Correspondence Analysis) reduces high-dimensional categorical data while retaining variance.
- **Clustering**: K-Means clustering identifies groups based on mental health risks.
- **Visualization**: Bar plots, pie charts, and t-SNE projections for cluster representation.
- **Cluster Profiling**: Summarizes key characteristics of each group for HR decision-making.

---

## Dataset
- **Source**: [OSMI Mental Health in Tech Survey 2016](https://osmihelp.org/research)
- **Features**:
  - Demographics (age, gender, country, work position).
  - Workplace environment (resources, policies, support systems).
  - Mental health attitudes and accessibility to resources.
- **Challenges**:
  - High dimensionality with 63 features.
  - Missing values and inconsistent text responses.
  - Need for categorization and standardization.

---

## Installation and Usage

### Prerequisites
- Python 3.7+
- Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `yellowbrick`

### Installation
1. Clone the repository:

git clone https://github.com/marierng/UnsupervisedLearning_FeatureEngineering.git
cd UnsupervisedLearning_FeatureEngineering

2. Install required Python packages:

pip install -r requirements.txt

3. Usage
Run the mentalhealth.py script to preprocess the dataset, apply clustering, and generate visualizations:


python mentalhealth.py
Ensure the dataset (mental-heath-in-tech-2016_20161114.csv) is in the same directory as the script.

# Results
The analysis identified four clusters with varying levels of mental health risk:

- High-Risk Group: Limited resources and accessibility to mental health support.
- Moderate-Risk Group: Adequate access but lack of proactive discussions.
- Low-Risk Group: Some resource access, but less frequent discussions.
- Ambivalent Group: Minimal support and accessibility.

# Visualizations include:
- Gender and country distribution.
- Correlation heatmaps to identify redundant features.
- Cluster representation in reduced dimensions using t-SNE.

# Limitations and Future Work
- The dataset may not fully represent all tech industry demographics.
- Responses may be subject to self-reporting biases.
- Future enhancements could involve integrating other datasets or testing advanced clustering algorithms.
