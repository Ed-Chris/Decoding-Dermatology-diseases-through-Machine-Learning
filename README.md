# Decoding Dermatology Diseases Through Machine Learning

## Project Overview
This project aims to leverage machine learning algorithms to enhance the differential diagnosis of erythemato-squamous diseases (ESDs), a group of skin conditions characterized by erythema and scaling. By utilizing various machine learning models, we aim to improve diagnostic accuracy and dermatological outcomes.

## Table of Contents
- Introduction
- Objectives
- Dataset
- Methodology
- Analysis
- Results
- Limitations and Future Work
- How to Run the Project
- Contributors
- References

## Introduction
Erythemato-squamous diseases (ESDs) are chronic, recurrent inflammatory skin conditions that are difficult to diagnose due to their overlapping clinical and histopathological features. This study utilizes machine learning algorithms to improve the differential diagnosis of six common ESDs, using a dataset from the UCI Machine Learning Repository.

## Objectives
1. Investigate factors influencing skin conditions.
2 .Develop and compare the performance of various machine learning models.
3. Classify the conditions and select the most efficient model for ESD diagnosis.

## Dataset
The dataset was obtained from the UCI Machine Learning Repository and contains 366 instances with 34 features. The features include clinical signs, histopathological attributes, and the patient's age. The class variable represents six types of ESDs:

- Psoriasis
- Seborrheic Dermatitis
- Lichen Planus
- Pityriasis Rosea
- Chronic Dermatitis
- Pityriasis Rubra Pilaris
- 
## Methodology
**Data Preprocessing**
- Missing Value Imputation: Dropped rows with missing values.
- Feature Scaling: Applied to standardize the dataset.
- Data Transformation: Used Linear Discriminant Analysis (LDA) to reduce dimensionality.

**Model Development and Training**
#### Developed and trained the following machine learning models:

- Logistic Regression
- Support Vector Classifier (SVC)
- K-Nearest Neighbor (KNN)
- Random Forest
- Gaussian Naïve Bayes
## Evaluation Metrics
- Accuracy
- Precision, Recall, and F1-Score
- Confusion Matrix

## Analysis
### Logistic Regression
- Original Data: Achieved an accuracy of 95.83%.
- LDA Data: Improved accuracy to 98.61%.
### Support Vector Classifier (SVC)
- Original Data: Achieved an accuracy of 97.22%.
- LDA Data: Improved accuracy to 98.61%.
### K-Nearest Neighbor (KNN)
- Original Data: Achieved an accuracy of 91.67%.
- LDA Data: Improved accuracy to 98.61%.
### Random Forest
- Original Data: Achieved an accuracy of 98.61%.
- LDA Data: Achieved an accuracy of 97.22%.
### Gaussian Naïve Bayes
- Original Data: Achieved an accuracy of 83.33%.
- LDA Data: Improved accuracy to 97.22%.
- 
## Results
The results indicate that the Random Forest model without LDA and Logistic Regression, SVC, and KNN models with LDA preprocessing showed the highest accuracy, making them the top choices for ESD classification.

## Limitations and Future Work
### Current Limitations
- Limited dataset size.
- Potential overfitting in some models.
- Lack of real-time diagnostic capability.

### Future Improvements
- Incorporate larger and more diverse datasets.
- Explore advanced algorithms like deep learning.
- Implement real-time diagnostic tools for clinical use.

## How to Run the Project
1. Clone the Repository:
git clone <repository_url>

2. Navigate to the Project Directory:
cd <project_directory>

3. Install the Required Libraries:
pip install -r requirements.txt

4. Run the Python Script:
python main.py

## Contributors
Yedu Krishnan

## References
Diagnosis of Erythemato-Squamous Skin Diseases by Machine Learning Algorithms. Link
Learning Differential Diagnosis of Erythemato-Squamous Diseases Using Voting Feature Intervals.
