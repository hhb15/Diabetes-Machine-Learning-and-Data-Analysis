# Diabetes-Machine-Learning-and-Data-Analysis
Worked in collaboration with Aaryaa Shah and Ashika Nadella

### Problem Statement
Diabetes is a major and growing public health challenge in the United States. Currently, 11.6% of the population (around 38.4M people) has diabetes. Of the entire U.S. population, 22.8% of adults with diabetes (around 8.7M people) remain undiagnosed. This project addresses that gap by predicting whether a person is at risk of developing diabetes. We will analyze data on diabetes health indicators and predict risks based on key indicators. 

### Strategic Aspects
We will start by cleaning and exploring our dataset on Kaggle and use machine learning techniques to build a model that predicts whether someone has diabetes. To make an accurate prediction, we want to ensure that the model takes into account biases related to age, gender, and ethnicity. We will analyze whether an individual’s health markers are above or below the average to check for biases. After creating the model, we will evaluate it and make adjustments based on its accuracy.

### Project Relation to Lectures and Course
This project will incorporate key concepts from this course, including machine learning, modeling, and data analytics. We will utilize tools such as Pandas, NumPy, Matplotlib, and scikit-learn to analyze our dataset and create models that predict outcomes based on key attributes. We will be performing analysis and visualization on the data we collect. The data will be cleaned and transformed to align with the course material. Machine learning techniques, as taught in lectures, will be applied to predict whether a person is at risk of developing diabetes. Techniques to improve the model, such as regularization and handling overfitting, will also be used. 

### Novelty and Importance
We believe that our project is important because our model will enable us to predict whether a person has diabetes based on their demographics, lifestyle choices, current health conditions, and medical history. Untreated diabetes can lead to long-term complications, including heart disease, kidney damage, peripheral neuropathy, or vision loss (Etudo). Therefore, with the help of the ML model we will develop, we are excited to enable early detection of diabetes, allowing patients to start treatment early and avoid complications that can lead to long-term effects.

### Current Issues
Some existing issues in current data science practices include incomplete data in datasets, inconsistent formats of data when derived from multiple sources, and a failure to consider features that can have an impact on the diagnosis of diabetes. Therefore, we hope to use datasets that have the majority of the data available, maintain consistency in terms of format and units, and consider all the potential features that can have an impact on the diagnosis of diabetes to minimize bias and ensure the model generalizes.

### Related Work
Several models have been developed to detect diabetes. For example, Adua et al. developed models, such as the Naïve Bayes model, with an accuracy of 87% to detect type 2 diabetes in the study’s participants based on their physical/health attributes, including BMI, HbA1c, and Total Cholesterol (TC). We hope to create a model that goes beyond blood work attributes, considering other features such as family medical history and diet for higher accuracy and improved generalization.

### Advantages and Limitations
The advantages of our approach include performing thorough data analysis of key features present in the Health & Lifestyle Data for Diabetes Prediction dataset, developing multiple variations of ML models to come up with the best-performing model, and also conducting comparative analysis with real-world datasets to increase generalization. The main limitation is that the NHANES Dataset didn’t include data for all of the features we used from the diabetes dataset, and therefore couldn’t compare all the features as we initially intended to. This occurred because we used features that go beyond the traditionally used metrics for the diagnosis of diabetes.

### Key Findings and Results
Overall, by working on this project, we found that although health attributes, such as glucose levels, primarily contribute to the diagnosis of diabetes, other lifestyle factors, including physical activity and diet, also have an impact on the diagnosis of diabetes. We reached this conclusion by incorporating multiple features in our model that go beyond traditional health factors. The results support our original hypothesis that we should not limit ourselves to blood work metrics in order to generalize and maximize the accuracy of the diagnosis. 

### Sources
1. https://www.verywellhealth.com/untreated-diabetes-5116080
2. https://transmedcomms.biomedcentral.com/articles/10.1186/s41231-021-00096-z
3. https://www.cdc.gov/diabetes/php/data-research/index.html
4. https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/DIQ_L.htm
5. https://www.kaggle.com/datasets/alamshihab075/health-and-lifestyle-data-for-diabetes-prediction/data
6. https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?Cycle=2021-2023
