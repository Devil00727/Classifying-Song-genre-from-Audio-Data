# Classifying Song Genre from Audio Data

Overview

This project focuses on classifying songs into genres based on audio features. Using the Echo Nest dataset, we analyze various musical attributes and apply machine learning models to accurately classify songs as either 'Hip-Hop' or 'Rock'.

Project Details

Domain: Data Science, Audio Data Analysis

Duration: April 2024 - May 2024

Guide: Prof. Prabhu Ramachandran

Tech Stack: Python, Pandas, Matplotlib, Seaborn, Scikit-learn

Dataset

The dataset is compiled by The Echo Nest, a research group specializing in music analysis. It contains various extracted features from songs, including:

Tempo

Energy

Danceability

Acousticness
Each song is labeled as either 'Hip-Hop' or 'Rock', serving as the ground truth for classification.

Key Tasks & Methodology

Exploratory Data Analysis (EDA): Visualizing and understanding data distributions using Pandas, Matplotlib, and Seaborn.

Hypothesis Testing: Conducted the Shapiro-Wilk test to verify data adherence to statistical assumptions.

Model Deployment:

Implemented Decision Tree and Logistic Regression models.

Achieved 0.92 precision and 0.95 F1-score for genre classification.

Installation & Setup

Clone this repository:

git clone https://github.com/your-username/song-genre-classification.git
cd song-genre-classification

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook Notebook.ipynb

Usage

The Jupyter Notebook contains step-by-step analysis and implementation.

Modify hyperparameters and model configurations as needed.

Experiment with different classifiers or feature engineering techniques to enhance performance.

Results

The best-performing model achieved 0.92 precision and 0.95 F1-score.

Classification results and visualizations are provided in the notebook.

Contributors

Vishal Gautam (IIT Bombay)

Guide: Prof. Prabhu Ramachandran

License

This project is open-source and available under the MIT License.

For more details, refer to Notebook.ipynb.

