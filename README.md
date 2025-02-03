# 🎵 Spotify & Credit Card Data Analysis

📌 Project Overview

This project explores two datasets: Spotify song attributes and Credit Card usage to derive meaningful insights using data mining, classification models, and statistical analysis. The goal is to understand song likability factors and credit card user behaviors through machine learning techniques such as k-Nearest Neighbors (k-NN) and Naïve Bayes Classification.

📂 Datasets

🎧 Spotify Dataset
Tracks: 2017
Features: 17 (e.g., danceability, energy, tempo, valence, acousticness)
Target Variable: Likability (Binary: 0 = Disliked, 1 = Liked)
💳 Credit Card Dataset
Records: 1,319
Features: 12 (e.g., income, expenditure, dependents, active cards)
Target Variable: Income Level (Categorical: Low, Medium, High)
🔄 Project Workflow

🎵 1️⃣ Spotify Song Analysis
✔ Load and explore Spotify dataset 🎧
✔ Convert numeric song attributes into scaled values
✔ Perform t-tests to find significant differences between features
✔ Apply k-NN classification to predict song likability
✔ Identify optimal k-value using accuracy metrics

💳 2️⃣ Credit Card Analysis
✔ Load and clean Credit Card dataset 📊
✔ Categorize income into bins (Low, Medium, High)
✔ Apply Naïve Bayes Classification for income prediction
✔ Compare training vs. validation accuracy
✔ Visualize feature distributions using bar plots

📈 Key Findings

🎵 Spotify Analysis:

Significant features for song likability: danceability, tempo, valence
k-NN Model Accuracy: Improved after feature selection (Optimal k=7)
Limitation: Numeric attributes alone do not capture subjective preferences like emotional impact 🎭
💳 Credit Card Analysis:

Dependents & Expenditure play a key role in income classification
Naïve Bayes Model Accuracy:
Training: 52.21% 📊
Validation: 49.34% 📊
Naïve Bayes performed 58.55% better than a naive rule classifier 🎯
🛠 Technologies Used

🖥 R Programming (tidyverse, ggplot2, caret, e1071)
📊 Data Visualization (scatter plots, regression plots, bar plots)
📈 Machine Learning (k-NN, Naïve Bayes)
📋 Statistical Testing (t-tests for feature selection)
