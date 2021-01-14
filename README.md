# Ad Spend Attribution
### Marketing Mix Modeling (MMM)

In this project we use data on advertising spend to attribute product sales across marketing channels.

The data is originally sourced from Kaggle, here:
- https://www.kaggle.com/purbar/advertising-data/download

For this project, we download the data from a link made available through University of Washington:
- https://library.startlearninglabs.uw.edu/DATASCI410/Datasets/Advertising.csv

#### Abstract

Our dataset consists of ad spend and sales in 200 market areas, over a given marketing campaign (for a single product). Our goal is to attribute ad spend to product sales and make a recommendation for future campaigns.

We use multi-linear regression to split product sales into base and incremental sales, attributing incremental sales to each ads channel.
