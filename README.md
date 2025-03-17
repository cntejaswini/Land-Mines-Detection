
# Land Mines Detection using Machine Learning  

## Project Overview  
This project applies machine learning techniques to classify landmines using environmental and sensor data from the UCI Machine Learning Repository. Several classification models, including Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors, Naive Bayes, and Support Vector Machines (SVM), were tested. The best-performing model, SVM with an RBF kernel, achieved an accuracy of 61.62%.  

## Problem Statement  
Unexploded landmines pose severe risks to civilians and hinder socioeconomic development. Existing detection methods are resource-intensive and require expert intervention. This project leverages machine learning to automate landmine classification, improving detection efficiency and safety.  

## Data Source  
- **Dataset:** Land Mine Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/763/land+mines-1).  
- **Features:** Sensor data under varying environmental conditions, including target type and terrain characteristics.  

## Methodology  

### 1. Data Preprocessing  
- Removed duplicates and handled missing values.  
- Encoded categorical features and scaled numeric data.  
- Identified and treated outliers.  

### 2. Exploratory Data Analysis (EDA)  
- Conducted univariate, bivariate, and multivariate analyses.  
- Visualized feature distributions and correlations using histograms, boxplots, scatterplots, and density plots.  

### 3. Machine Learning Models  
The following models were implemented and evaluated:  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Support Vector Machine (SVM)  

### 4. Model Evaluation  
- Models were trained and tested using a 70-30 train-test split.  
- Performance was measured using accuracy, precision, recall, F1-score, and confusion matrices.  
- Hyperparameter tuning was performed using grid search and cross-validation.  

### 5. Best Model Selection  
- **Support Vector Machine (SVM) with RBF kernel** was selected for its highest accuracy (61.62%).  
- Tuned hyperparameters:  
  - Cost (C) = 1  
  - Gamma (γ) = 0.1  

## Results  
| Model | Accuracy (%) |  
|--------|------------|  
| Logistic Regression | 48.2 |  
| Decision Tree | 55.7 |  
| Random Forest | 59.6 |  
| KNN (K=7) | 47.9 |  
| Naive Bayes | 49.5 |  
| **SVM (RBF Kernel)** | **61.62** |  

## Conclusion  
- Machine learning effectively classifies landmines based on sensor data.  
- SVM with RBF kernel performed best, achieving 61.62% accuracy.  
- Feature importance analysis highlighted environmental conditions affecting detectability.  

