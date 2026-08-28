# Network Intrusion Detection Using Deep Learning

## 📌 Project Overview

This project focuses on detecting network intrusions using Artificial Intelligence and Deep Learning techniques.

The main goal is to analyze network activity and classify it as either normal or malicious.

## 📊 Dataset

The project uses a cybersecurity intrusion dataset containing **9,537 records and 11 features**.

The target variable is:

* `attack_detected` — indicates whether an attack was detected.

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

* Removed the `session_id` column.
* Handled missing values using the mode for categorical data.
* Checked for duplicate records.
* Explored numerical features and potential outliers.
* Converted categorical features using One-Hot Encoding.
* Split the dataset into training and testing sets.
* Applied Min-Max normalization.
* Reshaped the data for CNN input.

## 🧠 Deep Learning Model

A **Convolutional Neural Network (CNN)** was implemented using TensorFlow/Keras.

The model consists of:

* Conv1D layer
* MaxPooling1D layer
* Flatten layer
* Dense layer
* Dropout layer
* Output layer with Sigmoid activation

The model was trained for **10 epochs** using the Adam optimizer and binary cross-entropy loss.

## 📈 Results

The model achieved the following results on the test set:

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 83.23% |
| Precision | 88.68% |
| Recall    | 71.63% |
| F1-Score  | 79.25% |

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🎯 Learning Outcomes

This project provided practical experience in:

* Data preprocessing
* Machine Learning
* Deep Learning
* CNN models
* Model evaluation
* Data visualization
* Cybersecurity

## 👥 Team

This project was developed as a collaborative academic project by a team of Computer Engineering students at Al-Aqsa University.

### Team Members

* Braa Mousa
* Raghad Talal Qwaider
* Malak Jamil Nashwan
* Raneen Helmi Alghamri

### My Contribution

I contributed to the project through data preprocessing, feature preparation, CNN model implementation, model training, performance evaluation, and data visualization.


Computer Engineering Student
Al-Aqsa University
