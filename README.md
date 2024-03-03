## Assignment: 12.2 - Term Project
## Course: DSC 530-T303-2243-1
## Name: Tae-Hyun Sakong
## Date: 03/02/2024

---

#### Overview
This project aims to identify good predictors of used-car sales in India. By analyzing a dataset of used car transactions, we explore how the vehicle's year, kilometers driven (KM_Driven), mileage, engine size, and maximum power (Max_Power) influence the likelihood of a car being sold.

#### Dataset: [Used Car Sales in India Dataset](https://www.kaggle.com/datasets/shubham1kumar/usedcar-data)

The dataset used in this project is sourced from Kaggle and represents the used-car market in India. It includes various details for each transaction, such as the vehicle's name, year, selling price, mileage, engine size, and whether or not the vehicle was sold.

#### Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy



### Analysis Highlights
Descriptive statistics and exploratory data analysis to understand the distribution of key variables.

Identification and handling of outliers using the Interquartile Range (IQR) method.

Analysis of probability mass functions (PMF) and cumulative distribution functions (CDF) for selected variables.

Correlation tests to explore linear relationships between predictors and the outcome.

Logistic regression modeling to predict the likelihood of a car being sold based on KM_Driven.

#### Results
The analysis revealed that while certain factors like mileage show a statistically significant correlation with the likelihood of a car being sold, the overall predictive power of individual variables is limited. The logistic regression model indicated a negative relationship between kilometers driven and the probability of a car being sold, albeit with limitations in predictive performance due to class imbalance.

Acknowledgments
This project was completed as part of the DSC 530 course at Bellevue University. Special thanks to Dr. Iranitalab for guidance and support throughout the project.

#### Author
Tae-Hyun Sakong
