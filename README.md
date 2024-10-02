This project analyzes a dataset from the Google Play Store using exploratory data analysis (EDA) techniques. The aim is to extract meaningful insights about app categories, 
ratings, reviews, and trends to understand the app marketplace on Google Play.


The notebook processes and analyzes the Google Play Store dataset, which includes the following features:

App: Name of the app
Category: Category the app belongs to
Rating: Overall user rating of the app (1 to 5)
Reviews: Number of user reviews
Size: Size of the app in MB and kbs
Installs: Number of times the app has been installed
Type: Free or Paid app
Price: Price of the app 
Content Rating: Age group the app is appropriate for
Genres: App genre(s)
Last Updated: The date the app was last updated
Current Version: Current version of the app
Android Version: Minimum Android OS version required


Goals
Clean the dataset by addressing missing values, and inconsistencies.
Analyze the distribution of ratings, reviews, and installs.
Identify the most popular app categories and their trends.
Generate visualizations to make the data more comprehensible.

Setup
Requirements:

Jupyter Notebook
Python 3.11

The following libraries:
pandas
matplotlib
seaborn
numpy



Methodology
The analysis is broken down into several steps:

Data Cleaning:

Handling missing data and invalid entries.
Converting data types where necessary (e.g., Installs to integers).
Dealing with outliers.
Data Visualization

Visualizing the distribution of ratings, reviews, installs, and app sizes.
Bar plots for the most popular categories.
Correlation heatmaps to identify relationships between variables.
Feature Engineering 
    Creating new feature 'Size_in_Mbs' for more granular analysis.

Statistical Analysis:

Identifying statistical relationships between app success metrics (ratings, installs, reviews) and app attributes (category, size, price).
Results & Insights
App Ratings: Analysis of how ratings are distributed across different categories and price points.
App Categories: Insights into the most popular categories based on the number of installs and ratings.
Price vs. Popularity: Understanding the relationship between app pricing (free vs. paid) and user engagement.
Size vs. Ratings: How the size of an app affects its rating and performance on the store.
Content Rating Analysis: Trends in content ratings and their impact on app downloads.

Conclusion
This notebook provides a comprehensive analysis of the Google Play Store dataset, offering valuable insights into the mobile app market. 
It can be used as a foundation for more advanced analyses or machine learning projects aimed at predicting app success factors.

