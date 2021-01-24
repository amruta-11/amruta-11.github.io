---
title:  "Data Science Projects"
classes: wide
# permalink: /datascience/
header:
  overlay_color: "#000"
  overlay_image: /images/overlay.jpg
  og_image: /images/overlay.jpg

# Holiday Sales
feature_row1:
  - image_path: images/holiday.PNG
    title: "Holiday Sales - Linear Regression"
    excerpt: "
    Using linear regression to build a best-fit model that can predict the holiday sales of a customers based on their purchase history for the past year"
    url: "https://www.kaggle.com/amruta11/holiday-sales-multiple-linear-regression"
    btn_class: "btn--primary"
    btn_label: "View project"

# US 2020 Election
feature_row2:
  - image_path: images/Election.PNG
    title: "2020 Presedential Elections - Exploratory Data Analysis"
    excerpt: "Performing the exploratory data analysis on the 2020 Presidential Election data and creating visualizations to gain insights from the dataset"
    url: "https://amruta-11.github.io/projects/ElectionData.html"
    btn_class: "btn--primary"
    btn_label: "View project"

# Seattle Crime - Part 1
feature_row3:
  - image_path: /images/seattle1.jpg
    title: "Seattle Crime Data Analysis - I"
    excerpt: "Performed exploratory data analysis and used the dplyr verbs to find the number of crimes occurred each year since 1973 and then joined the crimedata, police beats data and the census data for the seattle region. The outcome was a dataset with more than 500,000 observations and 47 variables and used this huge dataset in Part - II"
    url: "https://amruta-11.github.io/projects/seattlecrime1.html"
    btn_class: "btn--primary"
    btn_label: "View project"

#Seattle Crime - Part 2
feature_row4:
  - image_path: /images/seattle1.jpg
    title: "Seattle Crime Data Analysis - II"
    excerpt: "A continuation of the Seattle Crime Data - Part I. Performing data analysis to find out if there was any relationship between crime rates in Seattle and the educational attainment of the people."
    url: "https://amruta-11.github.io/projects/seattlecrime2.html"
    btn_class: "btn--primary"
    btn_label: "View project"

# Stats & Prob
feature_row5:
  - image_path: /images/stats&prpb.PNG
    title: "Statistics & Normal Distribution"
    excerpt: "There are two parts in this project. For the first part, I used the probability concepts to calulate the expected profits for the airlines, in case they overbook. For second part, calculated the summary statistic for height & citation datasets and plotted the histogram and normal distribution curve to find out how they differ."
    url: "https://amruta-11.github.io/projects/stats&prob.html"
    btn_class: "btn--primary"
    btn_label: "View project"

# Web Scraping
feature_row6:
  - image_path: images/NBAStat.png
    title: "Web Scraping & Analysis"
    excerpt: "
    For this project, I scrapped the statistics of the basketball players from Wikipedia pages to convert it into a Pandas data frame. Performed analysis of the data using Pandas, NumPy, and plotted the results using matplotlib and stored the results on the IBM cloud."
    url: "https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/72f1ac0f-3ada-4503-8977-54ffdcb481f6/view?access_token=b310bf58d3677e9b995bfa42e49caa19cf7436833275167a15903951d854f3d5"
    btn_class: "btn--primary"
    btn_label: "View project"
---

{% include feature_row id = "feature_row1" type="left" %}
{% include feature_row id = "feature_row2" type="left" %}
{% include feature_row id = "feature_row6" type="left" %}
{% include feature_row id = "feature_row3" type="left" %}
{% include feature_row id = "feature_row4" type="left" %}
{% include feature_row id = "feature_row5" type="left" %}
