# EDA_Project

# Google Playstore Exploratory Data Analysis

In this project, the aim is to conduct an Exploratory Data Analysis (EDA) on a dataset comprising information from the Google Play Store. The dataset in question is divided into two main parts: "Play Store Data.csv" and "User Reviews.csv". The "Play Store Data.csv" file includes various details about apps available in the Google Play Store, such as app names, categories, ratings, reviews, size, installs, type (free or paid), price, content rating, genres, last updated, current version, and Android version. Meanwhile, the "User Reviews.csv" file contains user-generated reviews for these apps, providing insights into user sentiment and feedback.

This project's core objective is to extract valuable insights and trends from the dataset, which could be beneficial for developers, marketers, and analysts to understand the current app market landscape on the Google Play Store. It involves cleaning the data by handling missing values, converting non-numeric values to a suitable numeric format for analysis, and deriving additional metrics that could offer deeper insights into app performance and user preferences.We will answer some business questions in this project that can help us get some important insight from data.



# Analysis

The analysis will include the following steps:

    1. Importing Libraries
    2. Reading Data
    3. Understanding the Data
    4. Data cleaning and preprocessing
    5. Data Visualization to communicate the results
    6. Conclusion

#  Data

Two data sets are used in this project which includes the following information:

Play store data:

    1. App - Name of the Application
    2. Category - Category of the Application
    3. Rating - Rating given to the Application
    4. Reviews - No of reviews given to the Application
    5. Size - Size of the Application
    6. Installs - No of downloads of the Application
    7. Type - Free or Paid
    8. Price - Price of the Application if it is paid
    9. Content Rating - It is Age appropriate or Not
    10. Genres - Type of Genre the Application belongs to
    11. Last Updated - When the last time the Application is Updated
    12. Current Ver - Current version of the Application
    13. Android Version - Minimum Android version required to run the Application

User reviews data:

    1. App - the name of the app the review is for
    2. Translated_Review - the text of the review (translated to English)
    3. Sentiment - the sentiment expressed in the review (positive, negative, or neutral)
    4. Sentiment_Polarity - a numerical score indicating the sentiment polarity (ranging from -1 to 1)
    5. Sentiment_Subjectivity - a numerical score indicating the sentiment subjectivity (ranging from 0 to 1)

# Requirements

To run this project, you will need to have the following packages installed:

    1. Python - Programming Language
    2. Numpy - Scientific computing library
    3. Pandas - Data manipulation library
    4. Matplotlib - Data visualization library
    5. Seaborn - Data visualization library

# Conclusion

These are the general conclusions that are drawn from this EDA:

 1. Family, games,Tool category has the most number of apps.Therefore the developer can aim for developing a high quality app in less popular categories as there can be a scope for exploration in categories that are less explored.

2. Highest concentration of reviews is among the apps thar are rated between 4 and 5 which indicates that users might be less inclined to review poorly rated apps.

3. There are differences in rating distributions across content ratings, most apps are rated above 4.0, with a trend toward a slightly lower median rating as the intended audience age increases. However, the "Adults only 18+" category bucks this trend, potentially due to the small number of apps with this rating.

4. Certain categories like "Personalization" ,"Medical" and "Tools" seem to have a relatively higher presence of paid apps. This could suggest that users may be more willing to pay for apps that offer utility or customization.

     Niche Markets: Categories with a lower overall number of apps, including paid apps, might represent niche markets. These could be areas where specialized apps cater to specific user needs, and there may 
     be opportunities for new entrants if they can provide value.

5. Mostly the paid apps lie below 50$ mark, this might be a strategy from developers to price the apps at a low entry price for impulse purchases by customers.

6. The number of data points for each year seems to increase over time, suggesting that more apps have been updated in recent years, or possibly that the number of apps in the store has been increasing.

7. In positive reviews: Words like "great," "love," "good," "best," and "awesome" are prominent, suggesting strong satisfaction with the apps.

    The most prominent words are "bad," "problem," "issue," "worst," and "annoying," indicating common themes in negative reviews.

8. Health and fitness category has a median sentiment polarity above 0.25 and the spread shows that mostly the reviews are positive. Categories with median line close to zero suggests neutral sentiment.

9. Broad Compatibility: A significant proportion of apps support a wide range of Android versions (e.g., "4.0.3 and up"), suggesting developers aim for broad compatibility to reach a larger user base.

    Modern Android Support: There is a notable percentage of apps that require more recent versions of Android (e.g., "5.0 and up"), indicating developers are taking advantage of newer Android features and 
    technologies.

    Fragmentation: The variety of Android versions supported reflects the fragmentation of the Android ecosystem. Developers must decide whether to target newer versions with more features or older versions 
    with a potentially larger user base.

    "Varies with device": This category is quite substantial, showing that many apps have different minimum version requirements depending on the device. This could indicate adaptive app development practices 
    where compatibility is tailored to individual device capabilities.These might be apps for specific companies as their inbuilt app.

10. No. of installs reduce as age restriction increases.

11. 93 % apps are free and only 7 % are paid apps. This tells us that mostly free apps are being preferred by developers and end users but as spending capacity of people increase, the 7% figure can grow in future.

12. Education and Event category has a high rating because these apps are fullfilling specific needs.

    Dating category shows lower rating as different users might have different feature expectations and current features of app might not fullfill it.
    So regular updates can help in such cases.

13. Number of reviews and installs are moderately correlated, while price does not show a significant correlation with any of the other variables. Additionally, ratings have a very weak correlation with reviews and installs, and almost no correlation with price.

14. A steep rise in app ratings trend starting from 2012 to 2013, this might be due to the boom of andrioid phone market or better app development.

    Uptrend in recent years as more sophisticated apps are being developed with good development practice.
