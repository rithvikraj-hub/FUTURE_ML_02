# Customer Support Ticket Classification & Prioritization

## Overview

This project uses Machine Learning and Natural Language Processing (NLP) techniques to automatically classify customer support tickets into predefined categories and predict their priority levels based on the issue description.

The model is trained using a customer support ticket dataset and utilizes TF-IDF vectorization along with a Linear Support Vector Machine (LinearSVC) classifier to identify ticket categories and determine ticket priority.

---

## Features

* Data preprocessing and cleaning
* Text vectorization using TF-IDF
* Ticket category classification
* Priority prediction
* Model evaluation using accuracy score
* Confusion matrix visualization
* New ticket prediction system
* Organized project structure for future enhancements

---

## Project Structure

```text
FUTURE_ML_02/

├── data/
│   └── customer_support_tickets.csv

├── images/
│   └── confusion_matrix.png

├── notebooks/
│   └── customer_support_ticket.ipynb

├── requirements.txt

└── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* TF-IDF Vectorizer
* LinearSVC (Support Vector Machine)

---

## Dataset

The dataset contains customer support tickets with the following fields:

* Issue Description
* Category
* Product
* Priority

The model uses the issue description text as input and predicts:

1. Ticket Category
2. Ticket Priority

---

## Workflow

1. Load and preprocess the dataset.
2. Clean and prepare ticket descriptions.
3. Convert text into numerical features using TF-IDF.
4. Split data into training and testing sets.
5. Train a Linear SVM classifier for ticket classification.
6. Train a second model for priority prediction.
7. Evaluate model performance using accuracy scores.
8. Visualize results using a confusion matrix.
9. Test the system with new customer support tickets.

---

## Machine Learning Models

### Ticket Classification Model

**Algorithm Used:**

* Linear Support Vector Classifier (LinearSVC)

### Priority Prediction Model

**Algorithm Used:**

* Linear Support Vector Classifier (LinearSVC)

### Feature Extraction

**Vectorization Technique:**

* TF-IDF Vectorizer

---

## Results

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Ticket Category Prediction
* Priority Prediction

### Sample Prediction

**Input Ticket:**

```text
My payment was deducted but order was not placed.
```

**Predicted Category:**

```text
Billing
```

**Predicted Priority:**

```text
High
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
jupyter notebook customer_support_ticket.ipynb
```

Run all cells in sequence to train the models and generate predictions.

---

## Future Improvements

* Deploy as a web application using Flask or Streamlit
* Add advanced deep learning models such as LSTM and BERT
* Implement real-time ticket routing
* Add sentiment analysis for customer feedback
* Improve model accuracy using hyperparameter tuning
* Build an interactive dashboard for support teams

---

## Conclusion

This project demonstrates how NLP and Machine Learning can automate customer support operations by classifying support tickets and predicting their priorities. Such systems help organizations reduce manual effort, improve response times, and enhance customer satisfaction.

---

## Author

**RithvikRaj Karakambadi**

