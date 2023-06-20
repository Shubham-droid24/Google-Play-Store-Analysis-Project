# Google Play Store Analysis
AlmaBetter Verified Project

![image](https://github.com/Shubham-droid24/Google-Play-Store-Analysis-Project/assets/72461022/ddfd967d-9d59-41c4-b8c8-94f1e0b2c548)


I have explored and analysed the google play store data to discover key factors that are important in making an app successful. I have done univariate, bivariate and multivariate analysis on the dataset provided.

## Problem Statement:

The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Each app (row) has values for catergory, rating, size, and more. Another dataset contains customer reviews of the android apps.
Explore and analyze the data to discover key factors responsible for app engagement and success.

## Why do we need to this project ?

With around three million apps available on Google Play Store, developing apps that stand out amongst the competition poses a challenge for app developers. To differentiate themselves in this oversaturated market, they need to pinpoint essential factors that play a role in customers’ decision-making process.
The objective of this project is to deliver insights to understand customer demands better and thus help developers to popularize the product. To clarify, the ‘popular’ in this project means a high number of installations.

## Summary:


The Play Store Data Analysis Project gave me a good experience of how to explore and analyse the dataset. My objective was to determine the factors responsible for App Success. Before exploring play store apps data, first imported all the libraries, mounted the drive and read the dataset. After this, explored head,tail, shape, columns, information of the dataset. Firstly, I understood the important features(columns) of it like Categories, Rating, Reviews, Installs, Size and Type of Apps. As I explored the dataset I came to know that some columns are not assigned the correct data types and there are some null values also. So I cleaned the data and filled or deleted the null values according to the number of null values in the respective columns of the dataset given. Secondly, I faced some problems with the values of particular features like data types of them were incorrect(eg:- 'Size' feature was of object datatype), so I cleaned them by replacing all the characters that make them of different datatype and assigned correct datatypes. Next, I dealed with the null values by either deleting or imputing(by mean values) them according to the number of null values in the respected features. Next, I analyzed the data and found some useful insights.

## Conclusion:

Some useful insights extracted are as follows:

1) Most number of apps are of category:- Game, Communication, Productivity, Social and Tools.

2) Most number of apps are having rating from 4.1 to 4.6.

3) Communication, Game, Social, Photography and Video players Categories got most number of average of reviews.

4) Most of the apps which are free have high ratings while for the paid apps, there is no significant distribtion between size and ratings.

5) Majority(80%) of the apps are for everyone in the play store.

6) From the correlation matrix and heatmap I came to know that there is not any considerable correlation among the features except reviews and installs(that is 0.64).

