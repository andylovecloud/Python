

# TOPIC 1: Supervised Learning (k-Nearest Neighbors Algorithm)



Supervised learning is a fundamental approach in predictive analytics, where a model learns from labeled data to make predictions. In this topic, we will focus on the k-Nearest Neighbors (kNN) algorithm, a simple yet powerful classification technique.

### Learning Materials:

## Lecture 01 Slides : Supervised Learning and the kNN Algorithm

Code Examples:

- [kNN Algorithm Using the sklearn Library](Topic-1/01_kNN_sklearn.ipynb): For hands-on implementation, use this notebook with sklearn to easily apply the kNN algorithm. (Recommended for Assignment 1)
- [kNN Algorithm from Scratch](https://deepnote.com/app/ndungu/Implementing-KNN-Algorithm-on-the-Iris-Dataset-e7c16493-500c-4248-be54-9389de603f16) (For Practice Only): Understand the inner workings of the kNN algorithm with a Python implementation built from scratch. (Note: This is for practice and not required for Assignment 1).
- [Euclidean Distance Notebook](Topic-1/Euclidean_Distance.ipynb)

#### Cross Validation:
Cross-validation is essential to ensure your model generalizes well to new data. We’ll use k-fold cross-validation with the kNN algorithm to assess performance.

- [kNN with k-Fold Cross Validation](Topic-1/02_kNN_kfold.ipynb) (Notebook): Explore how to implement k-fold cross-validation using sklearn and kNN to improve model reliability.

- [Explanation of k-Fold Cross Validation](https://machinelearningmastery.com/k-fold-cross-validation/) (External Link): Review this linked article for an in-depth explanation of k-fold cross-validation.

#### Additional Resources: Here are some resources to deepen your understanding about the field Data Science:

- What is Data Science: Understand the fundamentals of data science.

- Data Science vs. Machine Learning: Discover the differences between data science and machine learning and how they complement each other.


# TOPIC 2: Support Vector Machines (SVM)
Support Vector Machines (SVM) are powerful supervised learning algorithms primarily used for classification tasks, though they can also be applied to regression. SVM is highly effective in cases where the decision boundary is complex.

#### Learning Materials:

[Lecture Slides on Support Vector Machines (SVM)](https://docs.google.com/presentation/d/1wrXwPpTQ6099bhwubPyz5M9W705UyFvCyBI3XJG2B2s/edit#slide=id.g30f52f0f268_2_235):
An in-depth look at the theory and application of SVM, covering its foundation, types of kernels, and practical applications in classification.

#### Code Examples:

- [SVM Implementation with sklearn](Topic-2/01_SVM_Basics.ipynb) (Notebook): Practice building an SVM model using sklearn. This notebook will guide you through the basics of SVM implementation.

- [SVM with Different Kernels](Topic-2/02_Polynomial_SVM_Moons.ipynb) (Notebook): Explore the impact of different kernel functions (linear, polynomial) on SVM performance.

#### Additional Resources:

- scikit-learn SVM Documentation: [Comprehensive guide to SVMs in scikit-learn](https://scikit-learn.org/stable/modules/svm.html), covering implementation, kernels, and tuning options.
- Book: [Hands-On Machine Learning with Scikit-Learn - Chapter 5](https://hamk.finna.fi/PrimoRecord/pci.cdi_askewsholts_vlebooks_9781492032618?sid=4863288493)
- [Code Notebook from Book](Topic-2/Feature_Selection.ipynb)


# TOPIC 3: Unsupervised Learning (k-Means Algorithm)

Unsupervised learning involves finding patterns or groupings within data without labeled responses. The k-Means algorithm, a popular clustering technique, will serve as our main example for understanding unsupervised learning.

### Learning Materials:

- [Lecture Slides on Unsupervised Learning and the k-Means Algorithm](https://docs.google.com/presentation/d/1Gz-_sHmouEOO1FdmXHkOtB8iYXdstpqE3YWbZ_9VG7Q/edit#slide=id.g315f3b440ce_2_235): Gain insights into unsupervised learning concepts and explore the k-Means algorithm with these lecture slides.

- Code Examples:

    - [k-Means Algorithm](Topic-3/01_KMeans_Iris_Implementation.ipynb) (Notebook):A hands-on implementation of the k-Means algorithm in Python, applied to the Iris dataset.

    - [K-Means on Custom Dataset](Topic-3/02_KMeans_Income_Dataset.ipynb): Implementation of K-Means clustering on a small custom dataset containing fields like Name, Age, and Salary. ([Download the Income Dataset](Topic-3/income.csv)))

    - [k-Means Algorithm Example](https://www.kaggle.com/code/khotijahs1/k-means-clustering-of-iris-dataset) (External Link): Access an online example to see another implementation of k-Means in action (Kaggle).

- Additional Resources: 

    - [Machine Learning Cheat Sheet](Topic-3/azure-machine-learning-algorithm-cheat-sheet-july-2021.pdf): Refer to the Azure ML cheat sheet for guidance on selecting the best machine learning algorithms for various tasks based on data type and objectives.

    - [Scikit-learn documentation for K-Means](https://scikit-learn.org/1.5/modules/clustering.html#k-means): Comprehensive documentation detailing the implementation and usage of the K-Means algorithm in Scikit-learn.
