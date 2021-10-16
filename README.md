# Project1-Udacity-Data-Scientist
As part of the udacity.com Data Scientist nanodegree, this is project one of the program. This project involves a Jupyter Notebook analysis of a dataset I selected from Kaggle that shows Real Estate Data for a year's worth of properties sold on the NYC real estate market, found at: https://www.kaggle.com/new-york-city/nyc-property-sales.

In this analysis I employ the CRISP-DM process to answer the following three questions:

1. Does Manhattan or the borough in general have any effect in predicting the sales price of a property? 
2. Are older buildings selling better than newer buildings based on location?
3. Is there a correlation in sales with time of year and square footage for any particular borough? For exmample, are Manhattan apartments selling faster in the winter or are lofts in Brooklyn in higher demand during the summer months?

# Libraries Used
| Library | Description |
| :--- | :--- |
| Numpy |This is where numerical constants like np.nan came from|
| Matplotlib |This was the plotting library used for seeing bar charts and plotting data |
| Pandas |This is the work horse behind our analysis for reading in the DataFrame from the CSV file and performing various data analysis and preparation |
| Seaborn |This was used to generate our heatmap |
| Sklearn |Used for encoding categorical columns in order to be able to include them in our linear regression model |

# Motivation for this Project
As I looked over the available data on Kaggle.com the subject of New York City real estate drew my attention. Not only is this a subject which I have recent experience analyzing but also one which I have some personal experience as well. I lived in several apartments in Manhattan early in my career while working on Wall Street, I proposed to my wife in Times Square while on a horse and buggy tour. How much more New York does it get, right? And since then we have bought and sold a few houses ourselves once we left the hustle and bustle of the city to raise a family.

# Files in this Repository
| File | Description |
| :--- | :--- |
| Project1.ipynb | The Jupyter Notebook with our code and findings |
| README.md | The file you are currently reading |
| nyc-rolling-sales.csv | The Kaggle CSV file with the corresponding real estate data used for our analysis |

# Summary of the results
| # | Question | Results |
| :--- | :--- | :--- |
| 1 | Does Manhattan or the borough in general have any effect in predicting the sales price of a property? | **YES** it impacts the price by a 35% difference in r-square value. Although Queens and Brooklyn have more sales (more than 50% of the sales together), Manhattan has the higher priced sales (over 50% as seens above). |
| 2 | Are older buildings selling better than newer buildings based on location? | **NO** not really, the impact is only about a 4% difference in r-square value. This was a little surprising given older buildings are typically rent-controlled. |
| 3 | Is there a correlation in sales with time of year and square footage for any particular borough? For exmample, are Manhattan apartments selling faster in the winter or are lofts in Brooklyn in higher demand during the summer months? | **NO** none at all in fact. Neither SALE DATE nor SALE SEASON NUMBER made any difference in our r-square value model. |

# Acknowledgements
Several code snippets came from previous lessons in our Udacity Data Scientist program. Also, where employed I have credited various contributors from StackOverflow.com, kite.com, and the Data Science Stack Exchange at https://datascience.stackexchange.com. A big thank you to our instructors and all those involved in the Udacity program.
