# Data_Science-
Google play store Analysis
## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of the Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.


##  💾 Project Files Description

<p>This Project includes :-
  <li>Google Colab NoteBook</li>
  <li>Technical Documentation</li>
</p>


### Data Source:
- [Dataset](https://drive.google.com/file/d/15SLvsarYG1wRaiZm21cC8XRfiWg0yTc1) - Dataset taken from AlmaBetter


## Features

**App Category:** Category of the app. This could be beauty, business, entertainment, education...etc.

**Rating:** How users rate the app out of 5, with 1 being the lowest rating and 5 being the highest.

**Reviews:** The number of user reviews each app has received.

**Size:** The memory size needed to install the application.

**Installs:** The number of times each application has been installed by users.

**Type:** Whether the app is free or a paid app.

**Price:** The price of the app.

**Content Rating:** This column specifies the intended audience for the app. Can be for teens, mature audience, or everyone.

**Genres:** The sub-category for each app. Example: for the Education category, this could be Education: Pretend Play, for example.

**Last Updated:** Release date of the most recent update for the app.

**Current Ver:** The app's current version.

**Android Ver:** The oldest version of Android OS supported by the app.

## 🛠️ Builds with

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=Seaborn)

![GoogleColab](https://img.shields.io/badge/GoogleColab-orange?style=for-the-badge&logo=GoogleColab)



## Summary and Conclusion

Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, I have ulized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

To ensure data integrity,  began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. However, due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected the final results. Therefore, just replaced these null values with the mode of ratings.

After cleaning the data, I conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs.
