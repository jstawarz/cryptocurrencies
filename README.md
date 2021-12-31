# Cryptocurrencies

## Overview of Project

In this project, we are working with Martha at Accountability Accounting. Accountability Accounting is looking to offer a cryptocurrency investment
portfolio for its customers. Our task will be to generate a report that includes what cryptocurrencies are on the market and how they could be grouped
in order to create a classification system for this new investment. 

### Purpose

The purpose of this project will be to help Martha create a report on cryptocurrencies to present to the board of Accountability Accounting. 
Together,we will clean the data, utilize unsupervised machine learning to group the cryptocurrencies, and lastly create visualizations to 
demonstrate the findings. 

## Results

To begin our project, we first had to clean the data. This involved dropping cryptocurrencies that are not currently being traded or mined, 
and removing data with null values. Once the cleaning process had been completed, we were left with 532 tradable cryptocurrencies. 
We were then able to cluster the data and create the below 3 dimensional graph to reflect the different clusters of cryptocurrencies. 

![This is an image](https://github.com/jstawarz/cryptocurrencies/blob/main/results/3d_clusters.png)

We also created a table listing all 532 crptocurrencies. 

![This is an image](https://github.com/jstawarz/cryptocurrencies/blob/main/results/table_of_tradable_cryptos.png)

Lastly, we created a 2 dimensional graph of the Total Coin Supply versus the Total Coins Mined. Looking at this graph can help us understand
which cryptocurrencies still have coins to be mined, compared to others that have almost been mined completely. 

![This is an image](https://github.com/jstawarz/cryptocurrencies/blob/main/results/coin_supply.png)

### Summary

Overall, the findings help demonstrate that there are many cryptocurrencies with potential for investors. Currencies where the mining rates are
relatively low compared to the total coin supply could have good potential for invenstment. Further research of the currencies is warranted, 
however, the data and visualizations created give Martha and her team a potential starting point of which currencies deserve a deeper look.