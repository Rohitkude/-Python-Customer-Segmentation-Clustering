Mall Customer Segmentation with K-Means
Project Overview

This project demonstrates a complete customer segmentation analysis for a mall’s client base using unsupervised machine learning (K-Means clustering). The goal is to identify distinct customer groups based on their annual income and spending habits, and to derive actionable insights for targeted marketing strategies.

The methodology is inspired by the teachings of Gaelim Holland, a Senior Data Analyst with over 10 years of experience and founder of AbsentData, a trusted platform for aspiring data analysts.

Objectives

Perform Univariate, Bivariate, and Multivariate Analysis on mall customer data.

Apply K-Means clustering to determine the optimal number of customer segments.

Summarize and interpret each cluster using descriptive statistics.

Recommend the best marketing group for business strategy.

Dataset

File: Mall_Customers.csv

Features:

CustomerID – Unique customer identifier

Gender – Male/Female

Age – Age of the customer

Annual Income (k$) – Income in thousands of dollars

Spending Score (1–100) – Score assigned by the mall based on spending behavior

Technical Workflow

Data Loading & Exploration

Import libraries, load dataset, check missing values, view summary stats

Exploratory Data Analysis (EDA)

Univariate Analysis → Histograms & boxplots of Age, Income, Spending Score

Bivariate Analysis → Scatter plots & pairplots (e.g., Income vs Spending Score)

Data Preprocessing

Encode categorical variables

Feature scaling with StandardScaler

Machine Learning – K-Means Clustering

Use Elbow Method to determine optimal K

Fit model and assign cluster labels

Cluster Analysis & Visualization

Visualize clusters in 2D & 3D

Calculate mean values for each cluster

Interpret cluster characteristics (e.g., “High Income, Low Spending”)

Business Insights

Identify the most valuable segments

Suggest marketing strategies for each cluster

Key Results

The analysis revealed 5 customer segments:

Cluster 0: Low Income, Low Spending

Cluster 1: High Income, High Spending → 🎯 Target group for premium marketing

Cluster 2: Mid Income, Mid Spending

Cluster 3: High Income, Low Spending → Re-engagement potential

Cluster 4: Low Income, High Spending → Budget-conscious but valuable

(Note: Cluster descriptions depend on final model output)
