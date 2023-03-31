# Frequent Itemset Mining
This is my submission for the Lab assignment 2 in Data mining class. It is an implementation of Apriori algorithm in order to solve the problem of Frequent Itemset Mining.

## Read and explore the dataset
The dataset in this lab is a .csv file containing 10 thousand grocery transactions.

## Basic utility functions
- Cover of an itemset
- Absolute support of an itemset
- Relative support of an itemset
- Check if an itemset is frequent

## Apriori algorithm
- Join 2 k-itemset to form a k+1-itemset (_Cal_Self_Join()_)
- Prune step (_Prune_By_Apriori()_)
- Complete Apriori (_Frequent_Itemset_Mining_Apriori()_)
