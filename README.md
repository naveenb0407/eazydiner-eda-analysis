# eazydiner-eda-analysis
## Scraping and Analyzing Restaurant Trends: An EDA Approach Using EasyDiner Data

# 📊 Overview

This project focuses on web scraping and exploratory data analysis (EDA) of restaurant data collected from EasyDiner.
It aims to uncover patterns and insights in restaurant ratings, cuisines, discounts, and pricing across five major Indian cities.

The project demonstrates how to transform unstructured web data into actionable insights using Python, data cleaning, and visualization techniques.



#🎯 Objective

The main objectives of this project are to:

-Automate the extraction of restaurant data from EasyDiner using Python and BeautifulSoup.

-Clean and transform the scraped data into a structured dataset.

-Perform Exploratory Data Analysis (EDA) to identify trends in restaurant ratings, cuisines, and pricing.

-Visualize findings to highlight consumer behavior and market opportunities in the Indian restaurant industry.


#🧩 Problem Statements

1 Which cuisines are most popular in different localities?

2 Which areas have the highest concentration of top-rated restaurants?

3 Which restaurant types (Café, Fine Dining, Casual) offer the best discounts?

4 How do average prices and discounts vary across cities?

5 Is there a relationship between price, rating, and discount

#🗂️ Data Source

The dataset was obtained via web scraping from EasyDiner.
Data was collected for five major Indian cities:
-🏙️ Mumbai

-🌆 Pune

-🌃 Bengaluru

-🏡 Hyderabad

-🏛️ Ahmedabad

#🧠 Features Extracted

Feature	Description

Restaurant Name 	: Name of the restaurant

Rating	 :  Average user rating

Cuisine  :	Type(s) of cuisine served

Location	 : Area and city of restaurant

Approx. Cost for Two	: Estimated cost for two people

Discount	: Discount percentage on EasyDiner

#🧹 Data Cleaning and Preparation

The raw data contained inconsistencies, extra text, and symbols. The cleaning process involved:

Removing unwanted text like “View All” and special characters.

Standardizing names, cuisines, and price formats.

Handling missing values and formatting errors.

Adding a new LOCATION column for city-wise segmentation.

Exporting the final structured dataset for analysis.

#📈 Exploratory Data Analysis (EDA)

##🔸 Univariate Analysis

Most restaurants have ratings between 4.0–4.5, indicating good quality overall.

Discounts are mostly in the 30–35% range.

Multicuisine is the most common offering, followed by North Indian.

Top chains include One8 Commune, Punjab Grill, and Mirage.

##🔸 Bivariate Analysis

Price vs Rating: High ratings are observed across all price ranges.

Average Price by City: Mumbai is costliest; Ahmedabad is cheapest.

Discounts by City: Pune and Hyderabad show greater discount variability.

##🔸 Multivariate Analysis

Most restaurants charge between ₹1000–₹2500.

Discounts range between 30% and 80%, with limited effect on ratings.

Ratings remain high (4.0–4.5) across all price ranges.

Mumbai and Bengaluru are premium dining hubs.

#💡 Key Insights

##Aspect	Insight

⭐ Ratings	Most restaurants are rated between 4.0–4.5

🍛 Cuisines	Multicuisine dominates the dataset

💸 Pricing	Mumbai > Bengaluru > Pune > Hyderabad > Ahmedabad

🎁 Discounts	30–35% is most common

📍 City Trends	Mumbai is costliest; Ahmedabad most affordable

#🧰 Tools and Technologies Used

##Tool	Purpose

🐍 Python	Core programming language

🧩 BeautifulSoup	Web scraping

🧼 Pandas	Data cleaning and manipulation

📊 Matplotlib / Plotly	Data visualization

💾 CSV	Data storage format

🧠 Jupyter Notebook	Interactive analysis and visualization

#🏁 Conclusion

Most restaurants maintain strong customer satisfaction (4.0–4.5 ratings).

Multicuisine and North Indian cuisines are the most popular.

Mumbai has the highest average prices, Ahmedabad the lowest.

Discounts are typically around 30–35%, but do not guarantee better ratings.

EDA confirms that quality and service influence ratings more than pricing or promotions.

This analysis highlights how web scraping and data analytics can reveal real-world business insights from public web data.

#🔮 Future Enhancements

Automate scraping with Selenium or Scrapy.

Build an interactive Power BI or Streamlit dashboard.

Expand dataset to cover more Indian cities.

Use Machine Learning to predict restaurant ratings based on features like price, cuisine, and discount.

#👨‍💻 Autor 

*Naveen





