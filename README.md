# Unsupervised Learning: K-means Clustering on Country Data
![alt text](https://help-international.org/sites/default/files/images/CAM21488.jpg)
This project focuses on Unsupervised Learning technique called K-means Clustering which is applied on socio-economic and health data of 167 countries with the aim of categorising the countries to determine their economic backwardness and eligibility for a financial aid.

# Problem Statement
The HELP organisation is looking to provide financial aid to countries which are economically backward and in direst need of the aid. The HELP organization has raised around USD10 million and wants to effectively manage and distribute that funding to the countries in need.

# Task:
Classify the countries in categories based on their socio-economic and health factors which determine the overall development of the country.

# Data description:
There are 9 socio-economic and health factors for 167 countries.
- country : Name of the country
- child_mort : Death of children under 5 years of age per 1000 live births
- exports : Exports of goods and services per capita. Given as %age of the GDP per capita
- health : Total health spending per capita. Given as %age of GDP per capita
- imports : Imports of goods and services per capita. Given as %age of the GDP per capita
- Income : Net income per person
- Inflation : The measurement of the annual growth rate of the Total GDP
- life_expec : The average number of years a new born child would live if the current mortality patterns are to remain the same.
- total_fer : The number of children that would be born to each woman if the current age-fertility rates remain the same.
- gdpp : The GDP per capita. Calculated as the Total GDP divided by the total population.

# Method:
For this analysis, I opted for KMeans Clustering out of the other algorithms like Hierarchical Clustering. I have carried out the below process in this project.

1. Data Collection and Preprocessing
2. Exploratory Data Analysis - with useful insights
3. Visualizations of the important features
4. Managing outliers in the data
5. Scaling the data
6. Model building - Finding optimal number of clusters
7. Model fitting and predicting the cluster labels
8. Exploring the characteristics of each cluster
9. Conclusion

# Project code:
The code for this project is in the following pdf file - [unsupervised_learning_kmeansclustering](unsupervised_learning_kmeansclustering-2.ipynb)

In addition, the clustered countries are highlighted in a world map which can be seen in this image file. This world map showing the three classified groups was produced using Plotly module in Python. - ![Categorized_Countries_World_Map](https://user-images.githubusercontent.com/63712490/221548879-8e36df83-0859-4b51-8f08-7e12ace598c4.png)
