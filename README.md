# Fake News Detection

![License](https://img.shields.io/badge/license-MIT-blue)

This repository contains code for a Fake News Detection project using machine learning techniques. The project focuses on classifying news articles into fake or true categories based on their textual content. Various classifiers and regressions are employed, resulting in high accuracy scores.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Models and Classification](#models-and-classification)
- [Manual Testing](#manual-testing)

## Introduction

Fake news has become a significant issue in today's digital age. This project aims to build and compare different machine learning models for the detection of fake news articles. The models are trained on a labeled dataset containing both fake and true news articles.

## Dataset

The dataset used in this project consists of two CSV files:
- `Fake.csv`: Contains fake news articles.
- `True.csv`: Contains true news articles.

The dataset is sourced from [[dataset link here]](https://www.dropbox.com/scl/fo/pea3jo3kxnhktfagk39t8/h?rlkey=dzpwbmj6dob0vg3zd7a0lfnjy&dl=0) and is for educational purposes only.

## Data Preprocessing

Data preprocessing is a crucial step in any machine learning project. In this project, the following preprocessing steps are performed:
- Text cleaning: Removing special characters, URLs, HTML tags, and punctuation.
- Splitting the dataset into training and testing sets.
- TF-IDF vectorization: Converting text data into numerical vectors.

## Models and Classification

Several machine learning models are trained and evaluated for fake news detection. These models include:
- Logistic Regression
- Decision Tree Classifier
- Gradient Boosting Classifier
- Random Forest Classifier

All models are trained on the preprocessed dataset, and their performance is evaluated using accuracy scores and classification reports.

## Manual Testing

The project also includes the ability to manually test news articles. You can input a URL or text of a news article, and the trained models will predict whether it's fake or true news.

To manually test a news article using a URL, run the .ipynb file
