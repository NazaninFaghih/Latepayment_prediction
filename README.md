#  Energy Company Data Analysis

## Introduction

This project showcases my work as a data scientist on analyzing data from an energy company. The objective was to gain insights and identify trends in the data, particularly focusing on the factors influencing late payments by customers over the past year. By conducting exploratory data analysis (EDA), performing data cleaning, feature engineering, and applying machine learning algorithms, I aimed to develop a robust model that could predict and understand the relationship between late payments and various features.

## Dataset

The dataset used for this project consists of data collected from an energy company. It contains information about customers, including their age, payment history, and other relevant factors. The dataset required thorough cleaning and preprocessing before conducting any analysis.

## Exploratory Data Analysis (EDA)

To gain a better understanding of the data, I started with exploratory data analysis. During this phase, I examined the data's statistical properties, identified missing values, and handled outliers. EDA allowed me to uncover insights and trends that formed the foundation for further analysis.

One of the key findings from the EDA was the significant impact of customer age on late payments. This observation served as an important factor for subsequent analysis and feature engineering.

<img width="528" alt="Screen Shot 2023-07-06 at 8 19 34 AM" src="https://github.com/NazaninFaghih/Latepayment_prediction/assets/65536921/9aef24c4-1acd-4edc-9857-714befd2a4ca">


## Feature Engineering

To extract meaningful information from the dataset, I performed feature engineering. This process involved transforming and creating new features based on domain knowledge and data insights. In this project, I used statistical importance and random forest importance techniques to select the most relevant features and discard less significant ones.

By leveraging these techniques, I aimed to improve the performance and interpretability of the machine learning models.

## Machine Learning Algorithms

To build a predictive model for late payments, I experimented with three different machine learning algorithms: logistic regression, decision tree, and random forest. These algorithms were chosen for their ability to handle both classification tasks and feature importance analysis.

## Data Splitting and Model Training

Before training the models, I divided the dataset into training, testing, and validation sets. This step ensured that the models were trained on a representative portion of the data, evaluated on unseen instances, and fine-tuned using the validation set.

The training set was used to train each machine learning algorithm, and the testing set allowed for performance evaluation and comparison. Cross-validation was also applied to assess the models' robustness and generalizability.

## Model Evaluation and Fine-Tuning

After training and testing the models, I evaluated their performance using appropriate evaluation metrics. The primary goal was to identify the best-performing model for predicting late payments accurately.

Upon comparing the results, the random forest model exhibited the highest performance among the three algorithms. This model was selected as the final model for further analysis.

<img width="395" alt="Screen Shot 2023-07-06 at 8 18 21 AM" src="https://github.com/NazaninFaghih/Latepayment_prediction/assets/65536921/593dfb14-0a63-48a6-8705-0c6d78833b83">


## Partial Dependence Plots

To gain insights into the relationship between late payments and different features, I utilized partial dependence plots. These plots visualize the impact of a single feature on the model's predictions while holding other features constant.

By interpreting these plots, I could understand the effects of different factors on late payments and extract actionable insights.

![pic3_new](https://github.com/NazaninFaghih/Latepayment_prediction/assets/65536921/59c86b03-ee11-430a-bd4b-63781cb77bda)


## Conclusion

This project demonstrates my skills as a data scientist in analyzing and modeling data from an energy company. By performing exploratory data analysis, feature engineering, and applying machine learning algorithms, I successfully identified key factors influencing late payments and developed a predictive model with high accuracy.

The insights gained from this project can assist the energy company in implementing targeted strategies to minimize late payments and improve customer satisfaction.

By showcasing this project in my portfolio, I aim to demonstrate my ability to leverage data science techniques to tackle real-world problems effectively.
