# ANALYSIS OF IRIS FLOWER DATASET AND WRITING A FIRST GLANCE TECHNICAL REPORT

![Iris plant](https://github.com/Chisom0089/Iris-flower/assets/138637505/3ce4626c-cdca-48a3-bb9f-77fd099ce664)

FIG 1: IRIS FLOWER

# INTRODUCTION
The Iris dataset is a classic dataset in machine learning and statistics, often used for pattern recognition. It is one of the earliest known datasets used for evaluating classification methods.The Iris flower dataset can be accessed [here](https://archive.ics.uci.edu/dataset/53/iris)


# PROJECT OBJECTIVES
1. Iris flower dataset review.
2. Identification of initial insights and patterns.
3. Technical report with detailed observation of findings.


# DATA EXPLORATION
I loaded the dataset into Power Query Editor in Power BI. The dataset contains 150 rows and 5 columns of data. It is made up of 3 classes of Iris flowers with each class having 50 instances. I checked the dataset for duplicates, null values, outliers, and spelling errors and ensured all data types were correct. No duplicates or null values were found, and data types were consistent with the expected format.


# DATASET ATTTRIBUTE
The columns contains;
1. Sepal length in cm
   
2. Sepal width in cm
   
3. Petal length in cm
   
4. Petal width in cm
   
5. Class:
   
a. Iris Setosa
b. Iris Versicolour
c. Iris Virginica

# DESCRIPTIVE STATISTICS
MAXIMIUM VALUES:

a. Iris Virginica has the maximum petal length (6.90 cm), petal width (2.50 cm), and sepal length (7.90 cm).

MINIMIUM VALUES:

a. Iris Setosa has the minimum petal length (1.00 cm), petal width (0.10 cm), and sepal length (4.30 cm).

b. Iris Versicolour has the minimum sepal width (2.00 cm).

STANDARD DEVIATION:

a. Iris Virginica has standard deviations of 0.55 cm (petal length), 0.27 cm (petal width), and 0.63 cm (sepal length).

b. Iris Setosa has the minimum standard deviation for petal length (0.17 cm), petal width (0.11 cm), and sepal length (0.35 cm).

c. Iris Setosa has the maximum standard deviation for sepal width.

These statistics suggest that Iris Virginica tends to have larger petals and sepals compared to the other species, while Iris Setosa generally has smaller and more consistent measurements.


# VISUAL ANALYSIS
I carried out an analysis to determine the distribution and correlation between features.

![features distributions](https://github.com/Chisom0089/Iris-flower/assets/138637505/c573aa19-03ca-467c-be2c-b58b900c24d0)

From the visuals above, the following observations were made:

1. Iris Virginica: Highest average sepal length (6.6 cm), petal length (5.6 cm), and petal width (2.03 cm).

2. Iris Setosa: Least average sepal length (5.0 cm), petal length (1.5 cm), and petal width (0.24 cm).

3. Iris Versicolour: Least average sepal width (2.77 cm).

# CORRELATION ANALYSIS

![correlation of featues](https://github.com/Chisom0089/Iris-flower/assets/138637505/a5e4c7b8-7996-4925-9980-7bc5fddb33b8)

The correlation analysis revealed the following:

Positive Correlations:

a. Sepal length shows a positive correlation with petal length.

b. Petal length shows a positive correlation with petal width.

No Correlations:

a. Sepal width shows no correlation with petal width.

b. Sepal length shows no correlation with sepal width.

# CONCLUSION
The analysis of the 3 classes of Iris flower dataset revealed key differences in sepal and petal measurements among Iris Setosa, Versicolour, and Virginica. Positive correlations were found between sepal and petal dimensions. These findings give a good idea of how the different types of Iris flowers differ in size and shape. This helps in accurately identifying each flower type and understanding their growth patterns better.

For further analysis, advanced classification techniques, principal component analysis, clustering algorithms, exploring additional morphological features, time-series growth pattern studies, and comparative studies with other botanical datasets should be put into considerations. These approaches can enhance model accuracy and deepen understanding of plant morphology and growth.

Feel free to follow me on linkedin[](https://www.linkedin.com/in/chisomibemere/) and twitter[](https://x.com/IbemereJulia). This report is my first project as a Data Analyst Intern at HNG TECH, kindly read more and follow HNG using the links: [](https://hng.tech/internship) and [](https://hng.tech/hire)
