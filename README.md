
# Sampling Assignment

This program is designed to perform various sampling techniques on a given dataset and evaluate their impact on machine learning models.


## Links

 - [Dataset.csv](https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv)
 - [Sampling.ipynb](https://colab.research.google.com/drive/1ZPHrtQ0UBIH4xI95y8O7LehFIOGMbrEt?usp=sharing)
 


## Description
The following tasks are accomplished in this program:

#### 1. Download the Dataset:
The dataset is obtained from the following link: Creditcard_data.csv.

#### 2. Convert to Balanced Class Dataset:

Techniques discussed in the class are employed to balance the classes in the dataset.

#### 3. Create Five Samples:

Using the sample size detection formula discussed in the class, five different samples are created from the balanced class dataset.
#### 4. Apply Five Sampling Techniques:

Five different sampling techniques are applied to each of the five samples:
  -  Simple Random Sampling
  - Systematic Sampling
  - Cluster Sampling
  - Stratified Sampling
  - Bootstrap Sampling

#### 5. Apply Sampling on Five ML Models:

The samples are used to train five different ML models:
- Random Forest
- Logistic Regression
- Naive Bayes
- Decision Trees
- KNN
#### 6. Evaluate Model Accuracy:

The accuracy of each model is determined based on the sampling technique applied.


## Sampling Techniques Used
- Simple Random Sampling: Randomly selecting data points without any specific pattern or criteria.
- Systematic Sampling: Selecting every kth item from the dataset after randomly selecting a starting point.
- Cluster Sampling: Dividing the population into clusters and randomly selecting entire clusters for the sample.
- Stratified Sampling:Dividing the population into strata and ensuring each stratum is represented in the sample.
- Bootstrap Sampling:Sampling with replacement, allowing the same data point to be selected multiple times.

### Output

|                   | Simple Random Sample | Systematic Sample | Stratified Sample | Cluster Sample | Bootstrap Sample |
|-------------------|----------------------|-------------------|-------------------|-----------------|-------------------|
| Logistic Regression | 0.713973799          | 0.68558952        | 0.834061135       | 0.709606987     | 0.703056769       |
| KNN               | 0.5                  | 0.5               | 0.502183406       | 0.502183406     | 0.5               |
| Random Forest     | 0.552401747          | 0.552401747       | 0.5               | 0.5             | 0.5               |
| Decision Tree     | 0.552401747          | 0.537117904       | 0.550218341       | 0.552401747     | 0.548034934       |
| Naive Bayes       | 0.620087336          | 0.61790393        | 0.620087336       | 0.620087336     | 0.543668122       |




## Conclusion
#### Simple Random Sampling:

- Best Model: Logistic Regression
- Accuracy: 0.713973799

#### Systematic Sampling:

- Best Model: Logistic Regression
- Accuracy: 0.68558952

#### Stratified Sampling:

- Best Model: Logistic Regression
- Accuracy: 0.834061135

#### Cluster Sampling:

- Best Model: Logistic Regression
- Accuracy: 0.709606987
#### Bootstrap Sampling:

- Best Model: Logistic Regression
- Accuracy: 0.703056769


**Logistic Regression**  consistently achieved the highest accuracy across different sampling techniques.
