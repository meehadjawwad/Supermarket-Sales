## Table of Contents
1. [Data Analysis](https://github.com/meehadjawwad/Supermarket-Sales#data-analysis)
   * [First Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#first-layer)
   * [Second Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#second-layer)
   * [Third Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#third-layer)
   * [Recommendations](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#recommendations)

## Data Analysis
For a deep analysis, I used the pandas and matplotlib + seaborn python libraries, and also imported the data into Tableau.

### First Layer
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

### Second Layer
The second layer of analysis was conducted in Tableau, in which I examined Customer Ratings given combinations of two variables.

_Figure 6_:

![Fig. 6](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/gender_city.png)

_Figure 7_:

![Fig. 7](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/product_city.png)

_Figure 8_:

![Fig. 8](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/payment_city.png)

_Figure 9_:

![Fig. 9](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/gender_product.png)

_Figure 10_:

![Fig. 10](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/payment_product.png)

_Figure 11_:

![Fig. 11](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/screenshots/gender_payment.png)

### Third Layer


### Recommendations
