# College Feedback Intelligence System

## Project Overview

The College Feedback Intelligence System is an NLP-based project developed to analyze student feedback collected from different areas of a college.

The system uses Natural Language Processing techniques to preprocess feedback text and classify the sentiment of student responses as Positive, Neutral, or Negative.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Logistic Regression
- Google Colab

## Dataset

The dataset contains student feedback related to different college facilities and academic areas such as:

- Teaching
- Course Content
- Examination
- Lab Work
- Library Facilities
- Extracurricular Activities

The dataset was processed and converted into a suitable format for sentiment classification.

## Methodology

The project follows these main steps:

1. Dataset loading
2. Data preprocessing
3. Feedback cleaning
4. Sentiment label generation
5. Train-test splitting
6. TF-IDF feature extraction
7. Logistic Regression model training
8. Model evaluation
9. Sentiment prediction

## Model Used

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert the feedback text into numerical features.

### Logistic Regression

Logistic Regression is used as the classification algorithm to classify feedback into Positive, Neutral, and Negative sentiment categories.

## Results

The model achieved the following results:

- Accuracy: 79.64%
- Precision: 77.96%
- Recall: 79.64%
- F1-Score: 76.20%

## Project Structure


College-Feedback-Intelligence-System/
│
├── nlpproject.ipynb
├── requirements.txt
├── README.md
├── dataset/
├── screenshots/
└── report/