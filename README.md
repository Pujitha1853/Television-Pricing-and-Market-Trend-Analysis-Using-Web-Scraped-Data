# Exploratory Data Analysis – Television Pricing and Market Trends Dataset

This project performs **Exploratory Data Analysis (EDA)** on a **Television Product Dataset collected through Web Scraping** to understand pricing patterns, brand distribution, and product features available in the online TV market.

The analysis focuses on identifying **pricing trends, consumer preferences, and market segmentation** based on features such as resolution, screen size, brand, ratings, and warranty.

The insights generated from this analysis can help businesses understand **market positioning, pricing strategies, and product demand in the television industry.**

---

# Project Overview

Online marketplaces contain thousands of television listings with different prices, features, and specifications, making it difficult for customers to compare products effectively.

This project collects television product data using **web scraping**, cleans and processes the data, and performs **Exploratory Data Analysis** to discover useful insights.

The project answers questions such as:

* How does **TV resolution affect price**?
* Do **larger screen sizes lead to higher prices**?
* Which **brands dominate the TV market**?
* What is the **relationship between ratings, price, and product features**?

---

# Project Objectives

* Collect television product data using **web scraping**
* Clean and preprocess raw scraped data
* Analyze **pricing trends and market patterns**
* Identify relationships between **resolution, screen size, and price**
* Generate insights that support **better business and purchasing decisions**

---

# Dataset Information

**Dataset Name:** Television Product Dataset
**Source:** Flipkart (Web Scraped Data)
**Rows:** ~1000+ TV Listings
**Columns:** 13 after cleaning
**Data Types:** Numerical and Categorical

### Important Features

| Column         | Description                                   |
| -------------- | --------------------------------------------- |
| brand          | Television brand                              |
| price          | Current selling price                         |
| original_price | Original product price                        |
| discount       | Discount percentage                           |
| resolution     | Screen resolution (HD, Full HD, Ultra HD, 4K) |
| screen_size    | Size of the television screen                 |
| rating         | Customer rating                               |
| reviews        | Number of customer reviews                    |
| warranty       | Product warranty period                       |

The dataset contains **television product listings scraped from an e-commerce platform**.

---

# Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **BeautifulSoup / Requests** – Web Scraping
* **Jupyter Notebook**

---

# Data Cleaning & Preparation

The following preprocessing steps were performed:

* Collected raw data through web scraping
* Converted raw scraped data into a structured dataframe
* Removed unwanted symbols and text
* Separated combined fields into meaningful columns
* Handled missing values
* Removed duplicate records
* Converted price, rating, and review columns into numeric formats

### Key Observations

* Raw dataset contained **8 messy columns**
* After preprocessing, dataset expanded to **13 structured columns**
* **0% Missing Values**
* **0% Duplicate Records**
* Dataset became suitable for **statistical analysis and visualization**

---

# Exploratory Data Analysis

## Univariate Analysis

Univariate analysis helps understand the distribution of individual variables.

### Visualizations used:

* Histograms
* Box Plots
* Distribution Plots

### Key observations

* Most TVs are concentrated in the **lower to mid price range**
* TV price distribution is **right-skewed**
* Majority of customer ratings are around **4 out of 5**
* Ultra HD TVs appear frequently in the dataset

---

## Bivariate Analysis

Bivariate analysis explores relationships between two variables.

### Visualizations used:

* Scatter Plots
* Bar Charts
* Line Plots

### Key insights

* TV price increases as **screen size increases**
* Higher resolution TVs tend to have **higher prices**
* Premium resolutions like **Ultra HD and 4K** have higher average prices
* Warranty extension slightly increases TV prices

---

## Multivariate Analysis

Multivariate analysis helps identify relationships between multiple variables.

### Visualizations used

* Correlation Heatmap
* Brand Distribution Charts
* Resolution vs Price Analysis

### Findings

* Price shows strong correlation with **original price**
* Number of reviews strongly correlates with **number of ratings**
* Price has only **weak correlation with rating**
* Warranty shows **small influence on price**

---

# Key Insights

* **Ultra HD TVs have the highest average price in the market**
* **4K TVs receive the highest average ratings**
* Most TVs fall in the **budget and mid-range price segments**
* A few brands dominate the majority of TV listings
* Large screen TVs are positioned as **premium products**

---

# Business Recommendations

* Focus marketing on **mid-range TVs**, as demand is higher
* Use **competitive pricing strategies** for premium TVs
* Promote **high-resolution models** to attract tech-focused customers
* Maintain **balanced product portfolios across screen sizes**

---

# Conclusion

Exploratory Data Analysis revealed several important patterns in television pricing and market trends.

The analysis shows that **resolution, screen size, and brand positioning significantly influence TV pricing**.

The insights generated from this project can help businesses:

* Understand consumer preferences
* Improve pricing strategies
* Identify high-demand product segments

The dataset can also be used for **future predictive modeling**, such as predicting TV prices or customer preferences using machine learning.

