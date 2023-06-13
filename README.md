# Improved-k-NN-Breast-Cancer-Classification
This research aims to propose the implementation of feature selection using Recursive Feature Elimination with cross-validation (RFECV) could optimise the novel k-NN classification model to classify the Wisconsin Breast Cancer dataset which is based on the FNA technique with a more accurate, higher precision and better sensitivity.


# Abstract
Breast cancer is found to be the most common cancer worldwide that ranked one of the deadliest common causes of death in 2020. Hence, early identification of breast cancer is crucial to provide a higher chance of effective treatment and survivability. However, highly accurate breast cancer classification and identification techniques used by medical practitioners are too expensive. Therefore, this research takes advantage of the current Artificial Intelligence trend and utilised machine learning in the classification of breast cancer as it provides an accurate result at an affordable cost. In this research, K-Nearest Neighbors (k-NN) which is a popularly used machine learning for breast cancer classification had been further explored to improve its performance as it is sensitive to irrelevant features as these features will cause misinterpretation of neighbourhood information of target classes due to the uninformative distance measure irrelevant features provide during k-NN’s distance calculations. Consequently, the performance of k-NN will be affected. Ergo, the aim of this research is to overcome k-NN's limitation on sensitivity to irrelevant features through Recursive Feature Elimination with cross-validation (RFECV) which produced an optimised k-NN classification model. The RFECV will eliminate insignificant features recursively and selects the best number of features based on importance ranking. This research also employed hyperparameter tuning using the Elbow Method and Grid Search on the n_neighbours parameter of k-NN in order to produce a high-performance classifier. The dataset used in this research was obtained from the UCI Machine Learning Repository of index Wisconsin Breast Cancer Dataset (WBCD) which consists of two types of datasets namely WBCD (Original) and WBCD (Diagnostic). The model’s classification performance is evaluated on accuracy, precision and sensitivity. The classification result of WBCD (Original) is 97.06% accuracy, 96.67% precision and 96.67% sensitivity. Meanwhile, the WBCD (Diagnostic) achieved 98.21% accuracy, 94.74% precision and 100.00% sensitivity. In short, the proposed optimised k-NN model indeed produces a higher accuracy, precision and sensitivity performance outperforming the existing method and fulfilling the expected outcome of this research. 

# Research Aim
This research aims to propose the implementation of feature selection using Recursive Feature Elimination with cross-validation (RFECV) could optimise the novel k-NN classification model to classify the Wisconsin Breast Cancer dataset which is based on the FNA technique with a more accurate, higher precision and better sensitivity.
 
 
# Research Question
Advancement in technology has incorporated machine learning in breast cancer classification where the k-Nearest Neighbors (k-NN) classification model is one of the most popular supervised learning methods in cancer classification. However, the unsatisfactory results of the classification of breast cancer have been a perplexing issue as it involves many complex procedures and is usually exorbitant. 

   Thus, the main research question of this research is:

   How to improve the k-NN classification model for breast cancer classification in order to produce a higher accuracy and precision result?

The novel k-NN classification model can be improved in order to obtain a better classification accuracy of breast cancer classification (benign or malignant). To solve the complex procedures and expensive issues mentioned above, a feature selection method is needed to reduce the execution time, and steps to complete the machine learning stage led to an increase in classification accuracy.


# Research Objectives
There are two objectives that this research aims to achieve:
(a)	To propose an enhanced k-Nearest Neighbors (k-NN) with Recursive Feature Elimination with cross-validation (RFECV) classification model that produces high classification accuracy of benign and malignant breast tumours to overcome k-NN’s sensitivity to irrelevant features.
(b)	To evaluate the performance measurements of the proposed classification model in terms of accuracy and precision.

# Dataset
The datasets used in this research are obtained from UCI Machine Learning Repository derived from digitized images namely - Breast Cancer Wisconsin (Original) Data Set and Breast Cancer Wisconsin (Diagnostic) Data Set
(i)	Breast Cancer Wisconsin (Original) Data Set - https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29
(ii)	Breast Cancer Wisconsin (Diagnostic) Data Set - https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29


# Methodology
| Computational Methods                             | Category              | Implementation                                                                     |   |   |
|---------------------------------------------------|-----------------------|------------------------------------------------------------------------------------|---|---|
| k-Nearest Neighbors                               | Classifier            | Classify breast cancer datasets into benign or malignant classes.                  |   |   |
| Elbow Method                                      | Hyperparameter Tuning | Obtain the optimal K-value (n_neighbors) for k-NN for optimal performance.         |   |   |
| Grid Search-Based                                 |                       |                                                                                    |   |   |
| Recursive Feature Selection with Cross Validation | Feature Selection     | Select significant features to overcome k-NN’s sensitivity to irrelevant features. |   |   |
| 10-Fold Cross Validation                          | Cross Validation      | Data splitting to prevent underfitting or information loss.                        |   |   |

