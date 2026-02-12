# Lab 2: Machine Learning Problem Definition

## Dataset Overview
**Dataset Name:** Student Performance (student-mat.csv)
**Source:** UCI Machine Learning Repository
**Description:** This dataset contains social, gender, and study information about students in secondary education. It includes attributes like student age, parent's education, study time, and failures.

## Machine Learning Problem
**Problem Type:** Regression
**Target Variable:** G3 (Final Grade)
**Goal:** The goal of this project is to build a model that predicts a student's final grade (0-20) based on their study habits and family background. This can help identify students who need extra support.

## Methodology
The workflow follows these steps:
1. Load data using Pandas.
2. Preprocess data (convert categories to numbers).
3. Split into training (80%) and testing (20%) sets.
4. Train a Linear Regression model.
5. Evaluate using Mean Squared Error (MSE).
