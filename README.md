# Doctor Recommendation System

## Overview
The Doctor Recommendation System is a machine learning application designed to assist users in identifying the most suitable doctor based on their symptoms. This system leverages natural language processing (NLP) techniques and classification models to predict the medical specialization required and recommend relevant doctors.

## Features
- **Symptom Input**: Users can input symptoms in plain text.
- **Specialization Prediction**: The system predicts the required medical specialization.
- **Doctor Recommendation**: Recommends doctors based on the predicted specialization.
- **Data Visualization**: Includes visual representations of data distributions and model performance.

## Project Structure
- **Data Preprocessing**: Data cleaning, vectorization using TF-IDF, and label encoding.
- **Model Training**: Training classification models such as Logistic Regression and Random Forest.
- **Evaluation**: Metrics like accuracy and classification reports to assess model performance.
- **User Interface**: Interactive components for user input and recommendations.

## Requirements
- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - sklearn
  - nltk
  - matplotlib
  - seaborn
  
Install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

## How to Run
1. Install the required libraries as mentioned above.
2. Open the Jupyter Notebook `doctor_recommendation.ipynb`:
   ```bash
   jupyter notebook doctor_recommendation.ipynb
   ```
3. Run all cells in the notebook to execute the program.

## Usage
1. Load the dataset containing symptoms and associated doctor specializations.
2. Preprocess the data using the provided scripts.
3. Train the classification model.
4. Use the interactive interface to input symptoms and receive recommendations.

## Key Methods and Functions
- **Data Preprocessing**:
  - Cleaning and preparing text data.
  - Vectorizing textual inputs using TF-IDF.
- **Model Training**:
  - `LogisticRegression()`: Builds a logistic regression classifier.
  - `RandomForestClassifier()`: Implements a random forest model.
- **Visualization**:
  - Generates graphs to understand data distributions and model metrics.

## Results
- The system provides accurate predictions for doctor specializations based on input symptoms.
- Performance metrics demonstrate high accuracy with minimal overfitting.

## Future Work
- Enhance NLP capabilities to understand complex symptom descriptions.
- Expand the dataset for better generalization.
- Integrate with a web or mobile app for wider accessibility.
