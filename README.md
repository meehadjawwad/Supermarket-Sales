# Supermarket Sales

## Aim of the Project
The aim of this project was to:
- Conduct a deep analysis of Customer Ratings.
- Develop recommendations and provide actionable insights.

## Table of Contents
1. [Hardware Used](https://github.com/meehadjawwad/Supermarket-Sales#hardware-used)
2. [File Descriptions](https://github.com/meehadjawwad/Supermarket-Sales#file-descriptions)
3. [Methods Used](https://github.com/meehadjawwad/Supermarket-Sales#methods-used)
4. [Technologies Used](https://github.com/meehadjawwad/Supermarket-Sales#technologies-used)
5. [Deep Data Analysis](https://github.com/meehadjawwad/Supermarket-Sales#deep-data-analysis)
   * [First-Layer](https://github.com/meehadjawwad/Supermarket-Sales#first-layer)
   * [Second-Layer](https://github.com/meehadjawwad/Supermarket-Sales#second-layer)
6. [Executive Summary](https://github.com/meehadjawwad/Supermarket-Sales#executive-summary)
    * [The Data](https://github.com/meehadjawwad/Supermarket-Sales#the-data)
    * [Data Cleaning](https://github.com/meehadjawwad/Supermarket-Sales#data-cleaning)
    * [Data Exploration](https://github.com/meehadjawwad/Supermarket-Sales#data-exploration)
    * [Data Analysis](https://github.com/meehadjawwad/Supermarket-Sales#data-analysis)

## Hardware Used
- MacBook Pro (Retina, 13-inch, Early 2015)
- Processor: 2.9 GHz Dual-Core Intel Core i5
- Memory: 8 GB 1867 MHz DDR3
- OS: macOS Catalina (version 10.15.3)

## File Descriptions
- data:
  - supermarket_sales.csv: raw data file
  - supermarket_sales_clean.csv: cleaned data file
- jupyter_notebooks:
  - cleaning.ipynb: notebook for initial data cleaning.
  - analysis.ipynb: notebook for analysis.
- supermarket.pdf: presentation, including analysis and recommendations.
- requirements.txt: includes a list of python libraries used in the project.

## Methods Used
- Data cleaning
- Data exploration, analysis, and visualisation (python)
- Data exploration, analysis, and visualisation (tableau)

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Tableau
- Adobe Illustrator

## Deep Data Analysis
For a deep analysis, I used the pandas and matplotlib + seaborn python libraries, and also imported the data into Tableau.

### First-Layer
The first part of the analysis was conducted in Python, in which I explored the first-layer of Customer Ratings (single variables).

The average ratings across all variables was analysed, in light of the overall ratings.

_Figure 1_:

![Fig. 1](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/rating_analysis_1.png)

A custom function was defined to extract variables with ratings below the overall average.

_Figure 2_:

![Fig. 2](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/rating_analysis_2.png)

The distribution of the ratings was plotted, in order to assess the skew.

_Figure 3_:

![Fig. 3](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/ratings_distplot.png)

Finally, ratings were plotted against _total_price_ and _quantity_ in order to determine if any correlations existed.

_Figure 4_:

![Fig. 4](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/price_x_rating.png)

_Figure 5_:

![Fig. 5](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/quantity_x_rating.png)

The findings of the first-layer analysis are as follows:

- The highest overall rating is 10.0
- The lowest overall rating is 4.0
- The average overall rating is 6.97

- Mandalay's (branch) overall rating of 6.82 is below the overall average.
- Naypyitaw's (branch) overall rating of 7.07 is the highest among the three branches.

- The following product lines have an average rating which is below the overall average:
   - Electronic accessories
   - Home and lifestyle
   - Sports and travel

- Ratings between the lowest and highest are equally distributed.

- There are no correlations between ratings and _total price of transaction_ and/or _quantity_.

### Second-Layer
The second layer of analysis was conducted in Tableau, in which I examined Customer Ratings given combinations of two variables.

_Figure 6_:

![Fig. 6]

## Executive Summary
As stated earlier, there were two aims of this project:
- Conduct a deep analysis of Customer Ratings.
- Develop recommendations and provide actionable insights.

### The Data
The data, acquired from [Kaggle](https://www.kaggle.com/aungpyaeap/supermarket-sales), is the historical sales data of a supermarket chain spanning over 3 months. It contains transactions made by male and female, member and non-member customers, for 6 different product lines, using 3 different payment methods. In addition to sales data (such as price, quantity, gross income), it contains ratings scores (out of 10) for each transaction.

### Data Cleaning
All the column names were made more analysis-friendly and some of them were renamed for clarity. Repetitive, stationary, and unnecessary columns were dropped. Finally, the cleaned .csv file was exported.

### Data Exploration
The data includes 1,000 transactions and 13 columns.
Upon exploring the data, I was happy to conclude that all the variables (gender, branch, product_line, customer_type, payment_method) were fairly represented.

### Data Analysis
