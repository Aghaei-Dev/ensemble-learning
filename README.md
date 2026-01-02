# HASAN AGHAEI

---

## Hybrid Ensemble Learning: Classification and Clustering

## Project Overview

This project implements a **hybrid (ensemble) classifier** based on the aggregation of both supervised and unsupervised learning methods.

### Ensemble Classification Methods

- **MLP Neural Network** - Multi-layer Perceptron
- **RBF Neural Network** - Radial Basis Function Network
- **k-NN Algorithm** - k-Nearest Neighbors
- **GP Algorithm** - Gaussian Process Classifier
- **Naïve Bayes Algorithm** - Gaussian Naive Bayes

### Ensemble Clustering Methods

- **k-Means Algorithm**
- **k-Medoids Algorithm**
- **DIANA Algorithm** - Divisive Analysis

### Datasets

- **RCV1 (Reuters)** - Text classification dataset
- **Forest Covtype** - Forest cover type prediction dataset

### Evaluation Metrics

- **Classification**: Accuracy, Precision, Sensitivity (Recall)
- **Clustering**: Rand Index, F-measure

---

### Reports

after installing and importing the packages we need, we must load the data sets as below :

- RCV1 (Reuters) - Text classification dataset
  ![alt text](./images/3.png)
  ![alt text](./images/4.png)

- Forest Covtype - Forest cover type prediction dataset
  ![alt text](./images/1.png)
  ![alt text](./images/2.png)

after the loading the data we must split to test and train for both datasets:
![alt text](./images/5.png)

we need to train on the COVTYPE dataset and the optimal parameters as below:
![alt text](./images/6.png)
![alt text](./images/6.1.png)

results on COVTYPE as below:
![alt text](./images/7.png)

if you want a better view you can see this chart:
![alt text](./images/8.png)

after that we must find the proper weight of each model for ensemble Learner:
![alt text](./images/9.png)

and when we show the ensemble learner aside the base single learner we head to this chart:
![alt text](./images/10.png)

---

after that for clustering algorithms we have:
![alt text](./images/11.png)

and their optimal parameters.
![alt text](./images/12.png)

the results for clustering algorithms
![alt text](./images/13.png)

---

### Conclusion

![alt text](./images/14.png)
