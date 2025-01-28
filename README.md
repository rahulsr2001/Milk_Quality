# Milk Quality Detection Process

## 1.Data Collection
The dataset for milk quality detection includes various chemical and physical attributes of milk samples. Each row represents a sample, and each column corresponds to a feature or characteristic of the milk that influences its overall quality.

## 2.Data Preprocessing
Before training the models, the dataset was preprocessed, including handling any missing values, converting categorical variables, scaling numerical features, and splitting the data into training and test sets to ensure robust evaluation.

## 3.Feature Selection
The following features are selected for model training:

- **pH**: The pH value of the milk sample.
- **Temperature**: The temperature of the milk sample (°C).
- **Taste**: Whether the milk has a pleasant taste (1 = Yes, 0 = No).
- **Odor**: Whether the milk has a pleasant odor (1 = Yes, 0 = No).
- **Fat**: Whether the fat content is acceptable (1 = Yes, 0 = No).
- **Turbidity**: Whether the milk is turbid (1 = Yes, 0 = No).
- **Colour**: Numerical value representing the intensity of the milk's color.
- **Grade**: The quality grade of the milk (High, Medium, or Low).
## 4.Model Training
Several machine learning models were trained to predict the milk's quality grade. The models used in this task and their performance (accuracy) are as follows:

- Logistic Regression (LG): 78%
- Support Vector Machine (SVM): 85%
- Decision Tree (DT): 99%
- K-Nearest Neighbors (KNN): 99%
- Random Forest (RF): 99.6%
- Naive Bayes (NB): 91%
- XGBoost (XGB): 100%
## 5.Model Evaluation
The performance of each model was evaluated using accuracy scores, which measure the percentage of correct predictions on the test set. The XGBoost model achieved the highest accuracy of 100%, indicating perfect performance in classifying milk quality.

## 6.Best Model Selection
Based on the evaluation results, XGBoost, with an accuracy of 100%, is identified as the best-performing model for this milk quality detection task.
## Columns in the Dataset

Here is a detailed description of the columns used in the milk quality detection dataset:

- **pH**: The pH value of the milk sample, indicating its acidity or alkalinity.
- **Temperature**: The temperature of the milk sample in degrees Celsius (°C).
- **Taste**: A binary feature representing whether the milk has a pleasant taste (1 = Yes, 0 = No).
-**Odor**: A binary feature representing whether the milk has a pleasant odor (1 = Yes, 0 = No).
- **Fat**: A binary feature indicating whether the fat content in the milk is acceptable (1 = Yes, 0 = No).
- **Turbidity**: A binary feature indicating the turbidity of the milk (1 = Yes, 0 = No), where turbidity refers to the cloudiness or haziness of the milk.
- **Colour**: A numerical value representing the intensity of the milk's color, which may vary based on the milk's quality.
- **Grade**: The quality grade of the milk, categorized into three classes:
   - 1: High: The best quality milk.
   - 2: Medium: Moderate quality milk.
   - 3 : Low: Poor quality milk.

By analyzing important attributes like pH, temperature, taste, odor, fat content, turbidity, and color, machine learning models can classify milk into different quality grades. The XGBoost model is the most effective in this dataset, achieving perfect classification accuracy.
