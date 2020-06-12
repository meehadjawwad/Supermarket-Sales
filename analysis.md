## Table of Contents
1. [Data Analysis](https://github.com/meehadjawwad/Supermarket-Sales#data-analysis)
   * [First Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#first-layer-single-variable)
   * [Second Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#second-layer-two-variables)
   * [Third Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#third-layer-three-variables)
   * [Fourth Layer](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/analysis.md#fourth-layer-comparative-insights)

## Data Analysis
For a deep analysis, I used the pandas and matplotlib + seaborn python libraries, and also imported the data into Tableau.

### First Layer (Single Variable)
The first part of the analysis was conducted in Python, in which I explored the first-layer of Customer Ratings (single variables).

The average ratings across all variables was analysed, in light of the overall ratings.

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/rating_analysis_1.png' width='400'> |
| :--: |
| _Figure 1 - Single Variable Analysis_ |

A custom function was defined to extract variables with ratings below the overall average.

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/rating_analysis_2.png' width='400'> |
| :--: |
| _Figure 2 - Below Average Ratings_ |

The distribution of the ratings was plotted, in order to assess the skew.

| ![Fig. 3](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/ratings_distplot.png) |
| :--: |
| _Figure 3 - Distribution of Ratings_ |

Finally, ratings were plotted against _total_price_ and _quantity_ in order to determine if any correlations existed.

| ![Fig. 4](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/price_x_rating.png) |
| :--: |
| _Figure 4 - Relationship between Ratings and Total Price_ |

| ![Fig. 5](https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/quantity_x_rating.png) |
| :--: |
| _Figure 5 - Relationship between Ratings and Quantity_ |

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

### Second Layer (Two Variables)
The second layer of analysis was conducted in Tableau, in which I examined Customer Ratings given combinations of two variables.

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/gender_city.png' height='150'> |
| :--: |
| _Figure 6 - Ratings for different Cities according to Gender_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/product_city.png' height='270'> |
| :--: |
| _Figure 7 - Ratings for different Cities according to Product Line_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/payment_city.png' height='180'> |
| :--: |
| _Figure 8 - Ratings for different Cities according to Payment Method_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/gender_product.png' height='180'> |
| :--: |
| _Figure 9 - Ratings for different Product Lines according to Gender_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/product_payment.png' height='300'> |
| :--: |
| _Figure 10 - Ratings for different Payment Methods according to Product Lines_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/gender_payment.png' height='180'> |
| :--: |
| _Figure 11 - Ratings for different Payment Methods according to Gender_ |

The findings of the second-layer analysis are as follows:
- Male customers at Mandalay have given the lowest ratings.
- Male customers at Yangon have given the highest ratings.

- The Sports and Travel department at Mandalay has the lowest average ratings.
- The Fashion Accessories department at Naypyitaw has the highest average ratings.

- Customers paying with E-wallets at Mandalay have given the lowest ratings.
- Customers paying with credit-card at Naypyitaw have given the highest ratings.

- Female customers in the Home and Lifestyle department have given the lowest ratings.
- Female customers in the Food and Beverages department have given the highest ratings.

- Cash transactions in the Home and Lifestyle department have the lowest ratings.
- Cash transactions in the Food and Beverages department have the highest ratings.

- Male customers paying with cash have given the lowest ratings.
- Feale customers paying with cash have given the highest ratings.

### Third Layer (Three Variables)
The third layer of analysis was also conducted in Tableau, in which combinations of three variables were examined.

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/product_payment_gender.png' height='300'> |
| :--: |
| _Figure 12 - Ratings according to Product Line, Payment Method, and Gender_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/product_payment_city.png' height='240'> |
| :--: |
| _Figure 13 - Ratings according to Product Line, Payment Method, and City_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/product_city_gender.png' height='300'> |
| :--: |
| _Figure 14 - Ratings according to Product Line, City, and Gender_ |

| <img src='https://github.com/meehadjawwad/Supermarket-Sales/blob/master/images/payment_gender_city.png' height='210'> |
| :--: |
| _Figure 15 - Ratings according to Payment Method, City, and Gender_ |

The findings of the third-layer analysis are as follows:
- Female customers paying through E-wallet in the Sports and Travel department gave the lowest ratings.
- Male customers paying through credit-card in the Electronic Accessories department gave the highest ratings.

- Customers paying with cash in the Home and Lifestyle department at Yangon gave the lowest ratings.
- Customers paying with cash in the Food and Beverages department at Mandalay gave the highest ratings.

- Female customers in the Electronic Accessories department at Yangon gave the lowest ratings.
- Female customers in the Fashion Accessories department at Naypyitaw gave the highest ratings.

- Female customers paying through credit-card at Yangon gave the lowest ratings.
- Female customers paying through credit-card at Naypyitaw gave the highest ratings.

### Fourth Layer (Comparative Insights)
