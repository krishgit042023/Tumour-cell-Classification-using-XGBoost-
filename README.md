**🧬 Tumor Cell Classification using XGBoost**

A Machine Learning Project for Tumor Classification

This project focuses on classifying tumor cells as malignant or benign using the XGBoost classifier. The dataset contains features of tumor cells, and the goal is to accurately predict the class (malignant or benign) based on these features. The model utilizes K-fold cross-validation and achieves an impressive accuracy of 96.71%, with further improvement to 97.07% after applying Grid Search for hyperparameter tuning.

**📌 Project Overview**

The aim of this project is to classify tumor cells as malignant or benign using various features extracted from the tumor cell images. The XGBoost classifier is used as the primary algorithm due to its efficiency and performance in classification tasks. The project involves evaluating model performance using K-fold cross-validation and optimizing the model with Grid Search to further improve its accuracy.

**🛠 Technologies Used**

Programming Language: Python
Libraries:
XGBoost
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn
Tools: Google Colab

**📂 Dataset**

Description: The dataset contains various features related to tumor cells, including cell size, texture, and other statistical properties. The target variable indicates whether the tumor is benign (0) or malignant (1).
Key Columns:
Feature1, Feature2, ..., FeatureN: Various features of the tumor cells (e.g., size, texture)
Target: 0 for benign, 1 for malignant

**📈 Process Workflow**

Data Loading & Understanding:

Load the dataset using Pandas and perform initial data exploration.
Check for missing values, data types, and basic statistics.
Data Preprocessing:

Handle any missing values or outliers in the data.
Normalize or scale the features for optimal model performance.
Split the dataset into features (X) and target (y).
Model Training:

Apply K-fold cross-validation to evaluate model performance across multiple subsets of the data.
Train the XGBoost classifier on the training data.
Evaluate the model's accuracy and standard deviation from cross-validation.
Hyperparameter Tuning:

Perform Grid Search to tune hyperparameters and improve model accuracy.
Identify the best hyperparameters to achieve the highest accuracy.
Model Evaluation:

Measure performance using accuracy, standard deviation, and best accuracy after tuning.
Visualize confusion matrix and classification reports to assess model performance.
Final Model:

The best model achieved 97.07% accuracy after applying Grid Search.
