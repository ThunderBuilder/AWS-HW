# AWS-Homework

## Background

You are a Senior Manager at the Advisory Services team on a [Big Four firm](https://en.wikipedia.org/wiki/Big_Four_accounting_firms). One of your most important clients, a prominent investment bank, is interested in offering a new cryptocurrencies investment portfolio for its customers, however, they are lost in the immense universe of cryptocurrencies. They ask you to help them make sense of it all by generating a report of what cryptocurrencies are available on the trading market and how they can be grouped using classification.

In this homework assignment, you will put your new unsupervivsed learning and Amazon SageMaker skills into action by clustering cryptocurrencies and creating plots to present your results.

You are asked to accomplish the following main tasks:

- **[Data Preprocessing](#Data-Preprocessing):** Prepare data for dimension reduction with PCA and clustering using K-Means.

- **[Reducing Data Dimensions Using PCA](#Reducing-Data-Dimensions-Using-PCA):** Reduce data dimension using the `PCA` algorithm from `sklearn`.

- **[Clustering Cryptocurrencies Using K-Means](#Clustering-Cryptocurrencies-Using-K-Means):** Predict clusters using the cryptocurrencies data using the `KMeans` algorithm from `sklearn`.

- **[Visualizing Results](#Visualizing-Results):** Create some plots and data tables to present your results.

- **[Optional Challenge](#Optional-Challenge):** Deploy your notebook to Amazon SageMaker.

## Analysis Outputs

**K Means Elbow Curve**
---
![K Means Elbow Curve](Images/elbow.jpg)

- Most optimal value for k = 4

**Crytpo Class Summary from K Means Model**
---
![Crytpo class summary from K Means Model](Images/class.jpg)

**Crypto Summary by Circulating Supply & Total Coins Mined**
---
![Crypto Summary by Circulating Supply & Total Coins Mined](Images/crypto_supply.jpg)

**Crypto DataFrame for Tradeable Cryptos with Class Designation**
---
![Crypto DataFrame for Tradeable Cryptos with Class Designation](Images/crypto_df.jpg)

**Amazon AWS Sagemaker Data Load & Notebook Instance**
---
![Amazon AWS Sagemaker Data Load & Notebook Instance](Images/Sagemaker.jpg)
