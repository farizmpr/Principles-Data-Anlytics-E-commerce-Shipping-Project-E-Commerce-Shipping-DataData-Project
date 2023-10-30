
# Principles-Data-Anlytics-E-commerce-Shipping-Project-E-Commerce-Shipping-DataData-Project
Exploratory Data Analysis and Hypothesis Testing 
## Introduction
In this tech-driven era, the practive of online shopping has become deeply ingrained in the habits of the individuals. As a result, there is a growing quick but also safe, ensuring that products arrive to the destination on time.Sahoo et al. (2021) highlighted the pivotal role in shipping methodologies,including air, sea, and road, that have different inherent transport risks and serves as key performance indicators affecting the time of arrival. Nie (2022) further proposed that the modes of shipment are chosen based on the speed, safety, reliability, and cost-effectiveness.Hence , the transportation mode is an essential decision, especially for the e-commerce delivery. 

Moreover, in this project, the objective is to identify how different methods affect the time of arrival by using the hypothesis testing one-way ANOVA, which is using two different approcahes, and Kruskal-Wallis. The findings will show in statistical measure in graph which is examining the relationship. Lastly, the result will benefit the e-commerce company to support their comapny's project and support their assumption before putting them into action.

## Research Question
1. Is there any significant difference between mode of shipment and time of arrival in delivering package ?

## Data Collection
The data is come from "Customer Analytics" on Kaggle (https://www.kaggle.com/datasets/prachi13/customer-analytics). The dataset contains 10,999 observations across 12 variables. The variables provide comprehensive insights into customer behavior, shipping methods, and product delivery performance. Then, the two key factors used in the analysis :
* Mode of Shipment: Ship, Flight, and Road are three ways that the company transports its product
* Reached on time: it is a target variable, indicating whether products arrived on time (0 for on-time, 1 for delayed)
This research's focus is on exploring the relationship between shipping strategies and delivery effectiveness. The following sections of this report will provide more details about methodology, statistical techniques, research findings,and recommendations and suggestions for future.

## Methodology, concepts, and approaches
**The null and alternative hypotheses are defined below**:
* Null Hypothesis: The mode of shipment has no effect on the time of arrive of the order to the customer
* Alternative Hypothesis: THe mode of shipment affects the time of the delivery

**The Methodology**
* **One-Way ANOVA** :Comparing P-value to the chosen a value
* **One-Way ANOVA** :The test statistic to the critical region
* **Kruskal-Wallis** : considering the residual do not follow the normal distribution

**The EDA Goals**

* **Univariate Analysis**: proportion of the packages that arrive late or on-time
* **Univariate Analysis**: The amount of packages that arrive late or on-time
* **Univariate Analysis**: Distribution of each shipment for delivering package
* **Bivariate Analysis**: percentage/amount 1 and 0 in each mode of shipment
* Boxplot: To identify the outliers
