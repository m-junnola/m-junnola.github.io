## Portfolio

---

### Project 1: Impact of pandemic on household mortgages and consumer loans: Case COVID-19

Tools and data science tasks:<br>
-Python<br>
-Stata<br>
-Open data<br>
-Data preparation<br>
-Descriptive statistics<br>
-Data visualisation<br>
-Linear regression

This project is my bachelor’s thesis. The goal is to examine the impact of COVID-19 pandemic on household
mortgages and consumer loans during the first year of the pandemic. The study aims to find
whether the amount of household loans in Euro area countries are dependent on the number
of COVID-19 infections and hospitalized COVID-19 patients. Correlation between these variables 
is estimated by four regression models: two versions ordinary least squares regression,
fixed effects regression and random effects regression. The aim is to create a model that
explains high proportion of the variance of the amount of household mortgages and consumer
loans. Multiple control variables which explain the state of country’s economy and the state
of country’s households were included in the model to achieve this goal. The data consists of
information on 19 Euro area countries during 49-week period.
<br><br>
The most suitable estimation method was chosen according to statistical tests. As a result, the
fixed effect regression was chosen. According to fixed effect regression there is a statistically
significant positive correlation between mortgages and COVID-19 infections. The correlation
between consumer loans and infections as well as hospitalized patients is negative but statistically insignificant.
<br><br>
Full report in Finnish can be found from [here.](https://lutpub.lut.fi/bitstream/handle/10024/162734/Kandidaatintutkielma_Markus_Junnola.pdf?sequence=1&isAllowed=y)<br><br>

---
### Project 2: Linear regression with R 

Tools and data science tasks:<br>
-R<br>
-RStudio<br>
-Data preparation<br>
-Descriptive statistics<br>
-Data visualisation<br>
-Linear Regression<br>

This project was part of the final assignment of Free Analytics Environment R course.
In this assignment I obtained a dataset of historic data containing patient information,
including the patients’ blood glucose level, which can help to determine whether a patient may develop
(or have) certain illnesses. Thus, the goal was to use linear regression to determine what factors may
be linked to the blood glucose level in order to help doctors and patients to determine factors potentially
influencing the glucose level and to adjust their recommendations and treatment options accordingly. In
particular, my job was to make sense of the dataset from different perspectives and to build a regression
model that attempts to explain the blood glucose level of the patients.

The aim is to predict the blood glucose level of patients with the given features/ variables. The blood
glucose level of patients is represented by the variable Glucose, which is the dependent variable, and the
rest of the variables provide information to predict the value of the dependent variable.

At first I prepared the data, making sure that there are no missing or corrupted values and all variables are in the right data type. Then exploratory data analysis was performed followed by correlation analysis between all variables. Explanatory variables with correlation over 0.8 were removed to minimize multicollinearity in the model. Linear regression model was implemented with remaining variables. Statistically unsignificant variables were deleted from the model one by one. Deleting these variables had low effect on the R squared value. Final model's results showed that there is a strong correlation between high glucose levels and diabetes, and glucose levels can be lowered by consuming less sugar and consuming more foods with potassium.<br><br>

---
### Project 3: Clustering with R

Tools and data science tasks:<br>
-R<br>
-RStudio<br>
-Data preparation<br>
-Descriptive statistics<br>
-Data visualisation<br>
-Clustering with k-means algorithm

In this exercise I obtained a dataset containing information on customers 
and how they used the website of the e-commerce platform. Each row of the dataset represented a session of a unique customer on the website of the e-commerce platform. My task was to find similar types of users in terms of their usage behavior of the website and group them (via clustering). Moreover, the goal was to try to understand what are the characteristics of different groups and create a plan how to improve the business to benefit from this knowledge.<br>

At first dataset was prepared and exploratory data analysis performed to get a better understanding of the data. Correlation analysis was conducted to see the relationships between variables. To indentify clusters from the dataset k-means algorithm was used with Elbow method, Silhouette method,  Calinski-Harabasz index, and Gap statistic method. As a result two out of four methods suggested three clusters to be the optimal number of clusters. All three clusters had their distinctive attributes. Based on the characterics of each cluster a plan was created to increase the probability of a session ending into a purchase.<br><br>

---
### Project 4: CaseCalculator for Nordea Bank

Tools:<br>
-Excel<br>
-VBA<br>
-Power Query<br>

In this project I created an Excel program which calculates the number of non-collateralized loan applications
according to the type of the loan and by the customer segment. Previously the number of loan applications
were counted manually, which was very unefficient. With the help of this program our team was able to eliminate
an unnecessary stage in the working process.

---   

<!--
Tools

[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---
-->
