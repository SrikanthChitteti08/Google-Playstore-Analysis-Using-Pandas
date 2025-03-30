# **Google Play Store Apps Data Analysis**
This repository contains a Jupyter Notebook (Data_Preprocessing_With_Google_Playstore_1.ipynb) that performs data analysis on the Google Play Store apps dataset. The notebook covers data loading, preprocessing, and answering key questions about the dataset.

## **Dataset Overview**
The dataset contains information about 10,841 Android apps from the Google Play Store, with the following columns:

**App:** Name of the app

**Category:** Category the app belongs to

**Rating:** User rating of the app (1-5)

**Reviews:** Number of user reviews

**Size:** Size of the app

**Installs:** Number of downloads/installs

**Type:** Free or Paid

**Price:** Price of the app

**Content Rating:** Target audience age group

**Genres:** App genre(s)

**Last Updated:** Date of last update

**Current Ver:** Current version

**Android Ver:** Minimum Android version required

# **Key Analysis Performed**
## **Data Preprocessing**
**Loaded the dataset using pandas**

**Checked dimensions** (10,841 rows × 13 columns)

**Handled missing values by dropping rows with null values** (resulting in 9,360 clean rows)

## **Key Questions Answered**
**Average Rating:** The average rating of all apps is approximately 4.19

**Apps with Rating 5:** There are 274 apps with a perfect 5-star rating

**Apps with Rating 4-4.5:** 5,446 apps have ratings between 4 and 4.5

**Average Reviews:** The average app has approximately 514,376 reviews

**Categories:** There are 33 unique categories

**Apps per Category:** Breakdown of app counts for each category (e.g., FAMILY has 1,746 apps, GAME has 1,097 apps)

## **App Types:**

8,715 free apps (93.11%)

645 paid apps (6.89%)

## **Content Ratings:**

Everyone: 7,414 apps

Teen: 1,084 apps

Everyone 10+: 397 apps

Mature 17+: 461 apps

Adults only 18+: 3 apps

## **Conclusion:**
This analysis of the Google Play Store dataset provided valuable insights into app ratings, categories, pricing models, and content ratings.
