# Data-Analysis-Google Playstore app rating dataset


Play Store ratings for apps, and the corresponding proportional number of 1, 2, 3, 4, and 5-star reviews, are calculated based on the app's current quality ratings from user reviews, rather than the lifetime average value of user reviews unless the app has very few ratings. We are considering the dataset involving the details of apps having ratings to analyze the best emerging app.

## Project Synopsis

>> This repo contains Data Cleaning, Exploratory Data Analysis, and Data Visualization of Google Playstore app rating dataset taken from the Kaggle website [Click here](https://www.kaggle.com).

-------------------------------
## Project Walk-through

### Data Collection

Google Playstore app rating dataset taken from the Kaggle website consisted of 13 attributes and 10841 tuples, the attributes are:
 'App',
 'Category',
 'Rating',
 'Reviews',
 'Size',
 'Installs',
 'Type',
 'Price',
 'Content Rating',
 'Genres',
 'Last Updated',
 'Current Ver',
 'Android Ver'

------------------------------


## Data Cleaning

After collecting the data, checked for the null and duplicate values present in the dataset to provide better accuracy of the result by removing it. Changes I made and what all variables & scripts I wrote:

    * Dropped row of a Rating column that had an abnormal value of 19.
    * Dropped a few values that had not available values percentage of 90% empty. 
    * Filled missing values in a numerical column using the Median equation and categorical column using the Mode equation. 
    * Removed unnecessary parameters present in the data.
    * Converted into necessary datatypes.
-------------------------------
## EDA {Exploratory Data Analysis}

* All the imported distributions from the data cleaning data-set, I looked at the distributions of the data and the value counts for the various numerical and categorical variables.
* Using **Matplotlib & Seaborn**, categorized and crafted a beautiful data visualisation charts & plots
* Below are a few highlights from the *Pivot tables, Barplots & HeatMaps*.

![image](https://user-images.githubusercontent.com/98012611/155848837-ea64d4c1-2581-4f35-b013-c26010c72643.png)

![image](https://user-images.githubusercontent.com/98012611/155848850-0dcee5d5-4aa7-4076-9760-1057fac8d49f.png)

-----------------


## Resources Consumed for this project & where you can find them:

    Python Ver: 3.9.0
    Packages Used: Pandas, Numpy, Matplotlib, Seaborn, and Wordckoud.

* Matplotlib Documentation: [Click here](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html?highlight=boxplot#matplotlib.pyplot.boxplot)
* Seaborn Documentation: [Click here](http://seaborn.pydata.org/examples/many_pairwise_correlations.html)

-----------------------------
