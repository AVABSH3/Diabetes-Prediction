# Diabetes-Prediction-System
This repository contains the code for a Diabetes Prediction System using the SVM (Support Vector Machine) technique. The system predicts whether a person is likely to have diabetes based on various health features.

## Dataset
The dataset used for training and testing the model includes the following columns:

#### Pregnancies
#### Glucose
#### BloodPressure
#### SkinThickness
#### Insulin
#### BMI
#### DiabetesPedigreeFunction
#### Age
#### Outcome
Here's a snippet of the dataset:

| Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin | BMI  | DiabetesPedigreeFunction | Age | Outcome |
|-------------|---------|---------------|---------------|---------|------|---------------------------|-----|---------|
| 6           | 148     | 72            | 35            | 0       | 33.6 | 0.627                     | 50  | 1       |
| 1           | 85      | 66            | 29            | 0       | 26.6 | 0.351                     | 31  | 0       |
| 8           | 183     | 64            | 0             | 0       | 23.3 | 0.672                     | 32  | 1       |
| 1           | 89      | 66            | 23            | 94      | 28.1 | 0.167                     | 21  | 0       |
| 0           | 137     | 40            | 35            | 168     | 43.1 | 2.288                     | 33  | 1       |
## Methodology
The system employs the Support Vector Machine (SVM) algorithm for classification. Additionally, the data is standardized using the Standard Scaler to ensure consistent and optimal model performance.

## How to Use
Clone this repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the notebook or script to train and evaluate the model.
Utilize the trained model to make predictions on new data.


Feel free to explore and modify the code to suit your specific needs. If you encounter any issues or have suggestions for improvement, please open an issue.
