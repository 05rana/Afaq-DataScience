# Afaq (آفاق) — Tourism Engagement Analysis in Saudi Arabia

## Overview
Afaq is a data science and machine learning project that analyzes public engagement with tourism-related photos in Saudi Arabia using Flickr data. The project explores how visual elements, regions, seasons, and sentiment influence photo popularity.

## Objectives
- Identify underrepresented tourist destinations
- Analyze seasonal and regional engagement patterns
- Study the impact of visual elements on popularity
- Build predictive models for tourism engagement

## Data Sources
- Flickr API (favorites, metadata, comments)
- VisitSaudi (destination and season classification)
- OpenAI CLIP (image classification)
- OpenCV (day/night detection)
- Hugging Face Transformers (sentiment analysis)

## Dataset
- ~1000 images collected from Flickr
- 33 features includes engagement metrics, regions, seasons, sentiment, and visual elements

## Methodology
1. Data Collection via Flickr API
2. Metadata Extraction
3. Landscape & Seasonal Categorization
4. Image Classification (CLIP + OpenCV)
5. Sentiment Analysis
6. Data Cleaning and Feature Engineering
7. Exploratory Data Analysis
8. Machine Learning Modeling

## Models Used
- Linear Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)

## Results
- East region showed highest engagement
- South region showed lowest engagement
- Autumn was the peak season
- Daytime photos performed better
- Sand, roads, and rocks were top visual elements
- Random Forest achieved best performance (R² ≈ 0.93)

## Technologies
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- OpenCV
- Transformers
- CLIP

