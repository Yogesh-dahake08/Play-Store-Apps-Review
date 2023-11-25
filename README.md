# Play-Store-Apps-Review

**Project Summary**

Android is most popular Operating System with 2.5 Billion active user. Android is the dominant mobile operating system today with about 85% of all mobile devices running Google’s OS. The Google Play Store is the largest and most popular Android app store.

Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market.

Goals of Project - The purpose of our project was to gather and analyze detailed information on apps in the Google Play Store in order to provide insights on app features and the current state of the Android app market.

The Objective of our project to Explore and analyse the Data to discover key factor responsible for app engagement and recommend best fit and features that would lead to app success

We have tried to discover the relationships among various attributes such as which application is free or paid, what are the user reviews, rating of the application.

The data shared has each value(Row) has values for Category, Review, Rating, Size etc. with 10841 Rows and 13 Columns.


**Problem Statement**

Android is expanding as an operating system. It has captured around 74% of the total market which is a true indicator of the huge amount of population using android. Our goal is to help android developers to know what is the motivating factor for people to download an app. It will also help to find out the factors that affect someone’s decision to download an app. I would like to analyse category, reviews, price, ratings and installs for this purpose and find out how they are inter related.
There have some Problem Statements that are very useful for finding the insight from given Dataset -

Which category has most number of installations.
Top 5 app with the maximum installation.
Top 5 poor app in refrence of instaallation.
How Rating is important for Application.
Top Category on Play Store.
Find number of app in refrence of Free or Paid.
Define Your Business Objective?
The objective of my analysis is to provide insights about android applications and their categories.
To deep dive in data for the factors of influences on an application, to know why and how certain applications succeed and others.
Finds the key Factor that are responsible for app engagement.
Study the detailed information of app and analyse them.
Finds which attributes are most important for application.
Also, what is required for an application to be considered as successfully topping the charts.


**Conclusion**

In this project of analyzing play store applications, I have worked on several parameters which would help our client to do well in launching their apps on the play store.

92.2% of apps are of free type and 7.8% are paid
The minimum rating recieved in Education is 3.5, followed by Art and Design is 3.4, while the lowest ratings are recieved by Dating, Finance. Game, Tools, Communication, Business, productivity, Medical and family are 1. while the average ratings recieved by these categories are fairly good and above 4.1.
Ratio of paid and free apps in various categories we see that personalization and medical categories have mor paid apps percentage compare to other categories
the count of family apps is more compare to the other categories approximalty 1800 apps belong to the Family category where as Game category has around 950 apps
It is observed that the games have more installs followed by communication and tools
we found that 81.81% of apps can be rated by Everyone while 10.74% of apps are rated by teens, further the ratings and app usage is narrowed by everyone 10+ and mature 17+ with 4.07 and 3.33% respectively.
it is found that the max paid apps charge 0.99 dollars followed by 2.99 dollars and 1.99 dollars, this gives us a clue of having an affordable price of app is equally important.
Education, Beauty, Entertainment, parenting, weather and Maps and Navigation category have ratings distributed uniformly since there are less wiskers outside the box.
Ther ratings are normally distributed from 1 to 5 where the mean is 4.2 and median is 4.3, there was one outlier which was handled in data wrangling step.
With user df we found that 64.11% of recieved translated reviews are positive where as 22.10% of apps have negative sentiments and 13.79% of apps have neutral sentiments towards the apps whcih recied the reviews.
the Game categoy has most number of translated reviews followed by Family(plotted in chart 12 above)
when checking with sentiments accross various app categories we found that social apps have approximatly 50% of negative sentiments
We see that the correlation between Installs and Price is 0.63 which is good, It means that when there are more reviews on any app the more people tend to install the app. so its a better idea to get reviews on the app.
we found that there is a relation between the reviews and installs, the max installs the max reviews we get, the regression lines is liner and increases as (x=y approximatly)
The installs doesn't grow as the price increases.
Size and installs does not have relation.
the diagonal graphs in pair show the kde plotted wrt the own feature, it is noted that the diagonal plots doesnot follow the scale.
We categorised apps with various size into 4 category, That is Lite size, Medium Size, Large size, and extra large size and found that most of the people prefer to have lite size apps i.e 75% approx where as the other apps are marginally spread.(may depend on the use case and their increased functionality) extra large apps are of share 6% while medium and large apps share 9.5% of the total market.(as of 2018 data)
We see that most of the gaming apps are of all the size category and comunication apps are preferred to be made of lite size.
looking at trends we see most of the apps are tried to be made lite as it would lead to be a better option.
We extracted year of last update and found that most of the apps are recently updated and some of them have been not updated since a long time. For more detail analysis we can selectily visit the apps with old year of updates and check if the apps are stoped due to losses or closed.
We generated list of top apps with respect to Reviews, size, Installs, Price, top free. (listed in chart 19 section)
we found that some apps are duplicated with same names but different spelling, It is recommended to filter/get more accurate data. where as updating data with code would not be that easy to filter as there are spelling differences in the app names.(example I am Rich app)
