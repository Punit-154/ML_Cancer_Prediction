# ML_Cancer_Prediction

The goal of this project is to analyze medical diagnostic data, build a classification model using machine learning techniques, and predict whether a patient is likely to have cancer based on historical diagnostic features.

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

## Dataset

The dataset used contains medical diagnostic features of patients.
Each record includes multiple numerical attributes related to cell measurements.
The target label indicates:
Malignant (cancerous)
Benign (non-cancerous)
This dataset is commonly used for educational and research purposes in cancer classification problems.

## Project Workflow
## Step 1: Data Preprocessing
 -Loaded the dataset using Pandas.
 -Checked for missing values and handled them if present. 
 -Converted categorical labels into numerical format.
 -Performed basic Exploratory Data Analysis (EDA) to understand data distribution.

## Step 2: Model Building
 -Selected relevant features for prediction.
 -Split the dataset into training and testing sets.
 -Trained a classification model using Scikit-learn.
 -Used standard machine learning algorithms suitable for binary classification.

## Step 3: Evaluation & Visualization
 -Evaluated the model using accuracy and classification metrics.
 -Visualized results to compare actual vs predicted outcomes.
 -Analyzed model performance to understand strengths and limitations.

## Results
-The model was able to classify cancer presence with good accuracy on the test data.
-Demonstrates how machine learning can assist in early cancer detection.
-Highlights limitations due to dataset size and model simplicity.

## Future Improvements

-Experiment with advanced models (Random Forest, SVM, Neural Networks).

Perform feature selection and hyperparameter tuning.

Use cross-validation for better generalization.

Deploy the model as a simple web application using Streamlit or Flask.
