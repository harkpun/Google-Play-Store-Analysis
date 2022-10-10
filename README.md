# Google Play Store Analysis

Google Play Store is where you can download or buy millions of apps, games, and other media onto your Android device. Many apps will be free, some will have in-app advertisements, some will cost money, while others may offer in-app purchases, or a combination of any of these things.


## Table of Content
  * [Objective](#objective)
  * [Dataset](#dataset)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Project Structure](#project-structure)
  * [Technologies Used](#technologies-used)
  * [Inferences and Conclusion](#inferences-and-conclusion)

## Objective
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Explore and analyze the data to discover key factors responsible for app engagement and success.

## Dataset
The dataset contains web scraped data of 10k Play Store apps for analysing the Android market. It contains the first 'most relevant' 100 reviews for each app. Each review text/comment has been pre-processed and attributed with 3 new features - Sentiment, Sentiment Polarity and Sentiment Subjectivity.More details of the dataset can be found in the kaggle website.https://www.kaggle.com/lava18/google-play-store-apps#googleplaystore_user_reviews.csv

## Technical Aspects
This project is divided into two parts.
1. Data Preprocessing
      - Analyze and explore the data, converting dtype of columns from object to numerical or datetime format as per needed to make it ready for our analysis.
      - Dropping irrelevent columns, removing null values and deleting the duplicate row which are present in dataframe.
      - Imputing null values with Mean or Median for numerical attribute and Mode for categorical attribute. 
2. Data Visualization
      - Plotted several graphs and extracted more insights from our dataset which will help the developers in rolling out the app in the play store.

## Installation
This project requires python 3.6 or any other higher versions of python.
This project need software to run this python notebook "Jupyter Notebook" or "Google colab". It is highly recommended that you install the Anaconda distribution of Python or use "Google Colab" https://colab.research.google.com/, which already has most of the above packages and more included.
 

## Project Structure
```
├── README.md
├── Dataset 
│   ├── Play Store Data
│   ├── User Review Data
├── Process 
│   ├── Uploading Dataset 
│   ├── Abalyze Data
│   ├── Type Casting
│   ├── Data Imputation
│   ├── Data Cleaning
│   └── Data Visualization
├── Presentation
├── Report
├── Reference 
└── Result
```

## Technology Used
![image](https://user-images.githubusercontent.com/112171582/194882226-134ead9a-cb1c-4762-80bc-eee7472b037f.png)

## Inferences and Conclusion
In this EDA the given datasets are analysed and several graphs has been plotted which can be used to give more insights to the dataset.

* Distribution of Size shows most of the apps present in the play store are of smaller size.
* Minecraft is the only app in the paid category with over 10M installs. This app has also produced the most revenue only from the installation fee.
* Most of the apps present in the play store are available for everyone, there are very few apps which are having age restrictions.
* Content Rating Teen is having highest number of installs.
     - It shows that the present youths are quite good at operating apps and thus developers can develop more apps which suits to the interest of the teens.
* Number of free apps present in the play store are higher than paid apps.
     - It's quite evident users prefer to install free apps more as compared to the paid apps.
     - This gives direction that the developers can launch more of the free apps and for earning money.
     - They can use other means such as through advertisements in the apps or monetizing certain section of the app which serves certain special purpose or any other means.
* Game category has a greater number of positive reviews as well as negative reviews since there is more installs from the Game category.
* From the correlation matrix we can infer that reviews and installs are having a strong correlation.
     - It's quite evident as the more number of installs more will be the number of reviews.


The dataset contains possibilities to deliver insights to understand customer demands better and thus help developers to popularize the product. Dataset can also be used to look whether the original rating of the app matches the predicted rating to know whether the app is performing better or worse compared to other apps on the Play Store.


