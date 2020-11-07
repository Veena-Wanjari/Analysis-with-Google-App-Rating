# Analysis-Google-App-Rating

## __To Analyse__:

1. Which Category has the highest rating?
2. On which category, people are willing to spend more?
3. Which category has received highest reviews?

#### Libraries used: 
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [seaborn](https://seaborn.pydata.org/) 
* [matplotlib](https://matplotlib.org/)

## Steps taken to achieve solution.

1) Data imported from "googleplaystore.csv"

- data.describe() and data.info() shows that only one column "Rating" is numerical and rest all are string type.

- boxplot() and hist() give more indepth knowledge of the outliers and skewdness.

2) Data cleaning:   

- counting number of missing values
- removing columns that are 90% empty

3) Data Manupulation:

- Fill the null values with median for numerical columns.
- Fill the null values with mode for categorical columns.

6) Data Visualization:

Visualizing each mentioned problem with plot()

  * Category wise Rating
	
  * Category wise Pricing

  * Category wise Reviewing

7) Analysis:
 
## We can conclude that - 

a) Eventhogh the ratings are higher for Events and Education categories but people are tend to spend less. 
It is clearly visible with the  less money spent on buying Education app.

b) In Picing vs Categories people are buying Finance, Events and Lifestyle apps in comparision to gaming apps which is apparently very low.

c) People have reviewed as well as rated on Communication, Game and Social App but shying away from buying these apps.


