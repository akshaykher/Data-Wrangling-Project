# Retail-Analysis-Impact-of-Mailer-and-In-Store-Display

Project Link: http://rpubs.com/akshaykher/retailer_mailer_display_analysis

Data Link:

* product table link - https://www.dropbox.com/s/2hq56ye5tjp8ryb/product.csv?dl=0
* transaction_data link - https://www.dropbox.com/s/kqn5ontiyp3hvo0/transaction_data.csv?dl=0
* causal_data link - https://www.dropbox.com/s/n6x0ugtdna6av3t/causal_data.csv?dl=0

#### 1.1 Research Question
This project aims to explore the effect on sales, units and visits due to:

1. In-store display of a product
2. Whether the product was featured in the weekly mailer or not

For years, retailers have been investing in these two strategies to boost their revenues. At the same time, for years, consumers have been influenced by these two strategies without even knowing it. This project aims to quantify this effect and help both consumers and retailers.

#### 1.2 Data
The analysis will make use of transactional data and the causal data for a major retailer for a period of 2 years. The transactional data, as the name suggests, records all the transactions for 2500 households. The causal data records the display and mailer information for 68377 products in 115 stores.

#### 1.3 Methodology
Calculate the effect of in-store display and weekly mailer information on the sales, units and visits between Year 1 and Year 2 for the same:

1. Product
2. Store
3. Week ID

Once we have the information for distinct (a), (b) and (c) we can make generalized statements for all 68,377 products in 115 stores for the last 102 weeks. Using these results which are obtained from the sampled data, we will make use of central limit theorem and confidence intervals to make inferences about the population.

#### 1.4 Practical Usage
This project aims to quantify the effect of strategies discussed in 1.1 and help:

1. Retailers optimize their in-store display
2. Consumers optimize their spending on the right products with minimum influence
