# Python
## BasicDataAnalysis is the thing I learnt in 1st year


## Data-Processing is the thing I learnt in 2nd year
TOPIC 0: Recap on Jupyter Notebooks and some Python structures
This section provides a recap of the core concepts you’ve already covered in your first year of Python programming.

Notebook for starters
- [Markdown guide](https://markdown-guide.readthedocs.io/en/latest/basics.html)
- [Range-function](Data-Processing/Samples/01_range_function_python.ipynb) 

List, double and dict structures
 - [List](Data-Processing/Samples/02_Lists_Python.ipynb)
 - [Tuple](Data-Processing/Samples/03_Tuples.ipynb)
 - [Dict](Data-Processing/Samples/04_Dict.ipynb)
 - [Tuple assignment (often used in Python)](https://runestone.academy/ns/books/published/thinkcspy/Lists/TupleAssignment.html)

Slicing in Python
 - [Slicing notebook](Data-Processing/Samples/05_Slicing.ipynb)
 - [Tutorial for slicing](https://datadependence.com/2016/05/python-sequence-slicing-guide/)

List comprehension
 - [Tutorial for list comprehension](https://www.programiz.com/python-programming/list-comprehension)

 - [String Formatting](Data-Processing/Samples/06_String_Formatting.ipynb)


## Recommended Reading List for Data Processing with Python

The following book will be the primary course material for this class:

1. Python for Data Analysis (https://wesmckinney.com/book/)

This book by Wes McKinney provides a comprehensive introduction to data analysis with Python, covering key topics such as data manipulation, analysis with Pandas, and using Numpy and Matplotlib for scientific computing.

To enhance your understanding of the topics covered in this course, the following additional resources are recommended. These materials will support your learning in Python programming, data analysis, and visualization techniques, as well as the Numpy, Pandas, and Matplotlib libraries. You are encouraged to refer to them throughout the course.

2. General Python Programming

[Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) by Al Sweigart
This book is great for beginners, offering practical Python examples and exercises to help you automate common tasks with Python.
3. Numpy Library

[The Numpy Documentation](https://numpy.org/doc/stable/)
This is the official documentation for the Numpy library, covering everything from installation to advanced functions.

“Learning Numpy” by Ivan Idris
A beginner-friendly guide that introduces the Numpy library and how to use it for scientific computing.

4. Matplotlib and Data Visualization

[Matplotlib Documentation](https://matplotlib.org/stable/tutorials/index)
The official Matplotlib documentation offers detailed instructions on how to use the library for data visualization.

5. Pandas Library

[Pandas Documentation](https://pandas.pydata.org/docs/getting_started/index.html)
This is the official documentation for the Pandas library, covering data manipulation and analysis using DataFrames.

“Effective Pandas” by Matt Harrison
A concise and practical guide to mastering Pandas for data analysis tasks.



6. Additional Resources

“Real Python” ([realpython.com](https://realpython.com/))
An excellent resource with tutorials and articles on Python programming, data analysis, and visualization techniques.

“Kaggle” ([https://www.kaggle.com/learn/python](https://www.kaggle.com/learn/python))
Offers free tutorials and hands-on practice on Python, data analysis, and data visualization through Kaggle’s datasets.


### TOPIC 1: Numpy Library

The Numpy library is one of the core libraries for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with a wide range of mathematical functions to operate on these arrays efficiently. Numpy is essential for many data science and machine learning applications.

#### Numpy Learning Materials:
[1. Numpy Notebook:](/Users/Andy_1/Python/Data-Processing/Topic_1/01_Numpy.ipynb)
Explore Numpy's capabilities through a detailed notebook covering array creation, element-wise operations, indexing, slicing, broadcasting, and mathematical functions for efficient scientific computing.

[2. Speed Test: Numpy Arrays vs Python Lists:](/Users/Andy_1/Python/Data-Processing/Topic_1/02_Numpy_vs_List_Speed_Test.ipynb)
Explore how Numpy significantly improves computational efficiency by comparing the speed of element-wise operations in Numpy arrays (ndarrays) versus native Python lists through a detailed speed test experiment.

[3. Small Exercise for You:](/Users/Andy_1/Python/Data-Processing/Topic_1/BMI_Exercise_Notebook.ipynb)
Practice calculating Body Mass Index (BMI) for 10 individuals using both regular Python lists and Numpy arrays. This exercise will help reinforce your understanding of Numpy’s array manipulation and mathematical capabilities.

Additional Resources:
[Numpy Documentation & Homepage:](https://numpy.org/)
Learn more about Numpy from its official homepage, which includes full documentation and tutorials.

[Numpy Tutorial on W3Schools:](https://www.w3schools.com/python/numpy/default.asp)
Dive into the W3Schools Numpy tutorial for a deeper exploration of its functions and applications.

### TOPIC 2: Data Visualization

Data visualization is a crucial aspect of data analysis, enabling you to visually communicate insights, trends, and patterns effectively. Python provides several powerful libraries for creating informative and attractive visualizations. In this section, we will focus on two key libraries: Matplotlib and Seaborn.

#### Learning Materials:
1. [Matplotlib Notebook](Data-Processing/Topic_2/01_matplotlib_notebook.ipynb):
Explore the fundamentals of Matplotlib by learning how to create various types of plots such as line charts, bar charts, scatter plots, histograms, and pie charts

2. [Matplotlib with Real-World Dataset](Data-Processing/Topic_2/02_matplotlib_real_world_dataset.ipynb):
Apply your knowledge of Matplotlib to real-world datasets in this hands-on notebook.

3. [Seaborn Notebook](Data-Processing/Topic_2/03_seaborn_tutorial.ipynb):
Learn how to use Seaborn, a Python data visualization library based on Matplotlib that provides a high-level interface for creating attractive and informative statistical graphics.

#### Additional Resources:
- [Matplotlib Documentation & Tutorials](https://matplotlib.org/stable/tutorials/index.html): Learn more about Matplotlib from its official homepage, which includes extensive documentation, tutorials, and examples of various plot types.

- [Seaborn Documentation & Examples](https://seaborn.pydata.org/examples/index.html): Explore the Seaborn library through its official documentation, which provides tutorials, examples, and tips for customizing and enhancing your visualizations.

- [Matplotlib Tutorial on W3Schools](https://www.w3schools.com/python/matplotlib_intro.asp): Deepen your understanding of Matplotlib’s capabilities with a detailed tutorial on W3Schools, covering various plot types, customization options, and more.

- [Seaborn Tutorial on W3Schools](https://www.w3schools.com/python/numpy/numpy_random_seaborn.asp): Learn how to create advanced visualizations with Seaborn by exploring the W3Schools tutorial, which includes practical examples and step-by-step guidance.

### TOPIC 3: Data Manipulation with Pandas
Pandas is a powerful and versatile Python library for data manipulation and analysis. It provides data structures like Series and DataFrame to manage and analyze data efficiently, making it an essential tool for any data processing task. In this section, we will explore how to use Pandas for data cleaning, transformation, analysis, and manipulation.

#### Learning Materials:
#### [Pandas Fundamentals Notebook](Data-Processing/Topic_3/01_Pandas_Fundamentals_Notebook.ipynb):
Learn the basics of Pandas, including how to create and manipulate Series and DataFrame objects, handle missing data, and perform basic data operations such as filtering, grouping, and sorting.

#### [Pandas with Real-World Dataset](Data-Processing/Topic_3/02_Pandas_Real_World_Dataset_Notebook.ipynb):
Dive into practical applications of Pandas by working with real-world datasets [Download CSV Dataset]. This notebook will guide you through common data cleaning tasks, including handling missing values, transforming data, and preparing it for analysis.

#### [Advanced Pandas Operations Notebook](Data-Processing/Topic_3/03_Advanced_Pandas_Operations_Notebook.ipynb):
Explore more advanced Pandas features such as pivot tables, merging, joining, reshaping data, and working with time series data.

#### Additional Resources:
#### [Pandas Documentation & Tutorials](https://pandas.pydata.org/docs/getting_started/index.html): 
The official Pandas documentation, which provides a comprehensive guide to the library, including tutorials, examples, and best practices for data manipulation.

#### [Pandas Tutorial on W3Schools](https://www.w3schools.com/python/pandas/default.asp): 
A beginner-friendly guide to Pandas, offering practical examples and step-by-step instructions to help you master the library's core functionalities.

#### [Pandas Cheat SheetAvaa tämä dokumentti ReadSpeaker docReaderillä](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) : 
A quick reference guide for common Pandas operations, ideal for refreshing your knowledge or finding specific commands quickly.

### TOPIC 4: Analyzing Example Dataset
We will apply the data manipulation techniques learned in the previous topics to a real-world dataset. The dataset used here is a shop satisfaction survey that contains responses from participants along with relevant information about their demographics, purchasing behavior, and satisfaction levels.

You will learn how to do data cleaning, explore descriptive statistics, visualize the data, and examine the relationships between variables using cross-tabulation and hypothesis testing.

By the end of this session, you should be able to effectively apply data processing and analysis techniques to any dataset. You will use a similar dataset for your project.

#### Learning Materials:
 - [Dataset](https://docs.google.com/spreadsheets/d/1O11J6HpC9UL0F3y479JPOZgsN2FYPonZ/edit?gid=735537166#gid=735537166)
- [Analyzing Dataset Notebook](Data-Processing/Topic_4/Analyzing_ShopSatisfactionData.ipynb)


## Predictive Analytics with Python 2024 

### TOPIC 1: Supervised Learning (k-Nearest Neighbors Algorithm)

Supervised learning is a fundamental approach in predictive analytics, where a model learns from labeled data to make predictions. In this topic, we will focus on the k-Nearest Neighbors (kNN) algorithm, a simple yet powerful classification technique.

#### Learning Materials:

- [Lecture 01 Slides : Supervised Learning and the kNN Algorithm](https://docs.google.com/presentation/d/1jGgc_COPYduoBDRPieZGFmP_S8SRexajgXhZk4sHUyI/edit#slide=id.g30f52f0f268_2_272)

#### Code Examples:

- [kNN Algorithm Using the sklearn Library](Predictive-Analysis/Topic-1/01_kNN_sklearn.ipynb): For hands-on implementation, use this notebook with sklearn to easily apply the kNN algorithm. (Recommended for Assignment 1)
- [kNN Algorithm from Scratch (For Practice Only)](https://deepnote.com/app/ndungu/Implementing-KNN-Algorithm-on-the-Iris-Dataset-e7c16493-500c-4248-be54-9389de603f16): Understand the inner workings of the kNN algorithm with a Python implementation built from scratch. (Note: This is for practice and not required for Assignment 1).

- Cross Validation: Cross-validation is essential to ensure your model generalizes well to new data. We’ll use k-fold cross-validation with the kNN algorithm to assess performance.

- kNN with k-Fold Cross Validation (Notebook): Explore how to implement k-fold cross-validation using sklearn and kNN to improve model reliability.

- [Explanation of k-Fold Cross Validation (External Link)](https://machinelearningmastery.com/k-fold-cross-validation/): Review this linked article for an in-depth explanation of k-fold cross-validation.

#### Additional Resources: Here are some resources to deepen your understanding about the field Data Science:

- [What is Data Science](https://www.javatpoint.com/data-science): Understand the fundamentals of data science.

- [Data Science vs. Machine Learning](https://www.javatpoint.com/data-science-vs-machine-learning): Discover the differences between data science and machine learning and how they complement each other.


