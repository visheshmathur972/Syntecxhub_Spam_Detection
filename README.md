# Spam Detection using Machine Learning

## Project Overview
This project detects whether a text message is Spam or Ham using Machine Learning.

## Dataset
The dataset contains two columns:
- `label` — Spam or Ham
- `message` — Text message

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Naive Bayes
- Jupyter Notebook

## Methodology
1. Loaded the labeled spam/ham dataset.
2. Checked the dataset for missing values.
3. Prepared text messages and labels.
4. Split the dataset into training and testing data.
5. Converted text into numerical features using TF-IDF.
6. Trained a Multinomial Naive Bayes classifier.
7. Evaluated the model using Accuracy, Precision, Recall and F1 Score.
8. Created a confusion matrix.
9. Tested the model with a new message.
10. Saved the complete TF-IDF and model pipeline.

## Model
The project uses:
- TF-IDF Vectorizer
- Multinomial Naive Bayes

## Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Project Files
- `spam.csv` — Dataset
- `Spam_Detection.ipynb` — Jupyter Notebook
- `spam_detection_pipeline.pkl` — Saved Machine Learning pipeline
- `README.md` — Project documentation