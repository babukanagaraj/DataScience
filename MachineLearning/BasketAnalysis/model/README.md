# Basket Data Analysis

## 1. Purpose of Basket Data Analysis

* To understand the **customer purchasing pattern** in the supermarket.

* Identify the **frequent items sold** in the supermarket.

* Identify the frequent **items that are sold together** in the supermarket.

* With the insights, **formulate the strategy** that can be followed in boosting the item sales.

## 2. Problem Statement

* Identify the items and the itemset that creates a huge impact in driving the revenue and profit growth of the Supermarket business.

## 3. Supermarket Data transaction information

* The transaction dataset contains,
  *  _9835 rows and 1 column_

* Each row is a transaction and represents the items that are sold in that transaction. Refer the data directory for the dataset.

## 4. Exploratory Data Analysis

### 4.1 What is the maximum number of items that are sold in a transaction?

![No of items in Txn](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Txn.png)

* _The maximum number of items sold in a transaction is 32_.

### 4.2 What are the top selling items in the supermarket?

![Top selling items](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/TopSellingItem.png)

* _There are 169 unique items in the dataset_.

* _Canned beer is the top selling item in the supermarket_.

### 4.3 What are the top 5 frequent individual items sold in the supermarket?

![Top 5 Frequent Item](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Top5FrequentItem.PNG)

### 4.4 What are the top 5 frequent itemsets sold in the supermarket?

### 4.4.1 Itemset 1

![Itemset 1](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Itemset-1.PNG)

### 4.4.2 Itemset 2

![Itemset 2](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Itemset-2.PNG)

### 4.4.3 Itemset 3

![Itemset 3](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Itemset-3.PNG)

### 4.4.4 Itemset 4

![Itemset 4](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Itemset-4.PNG)

### 4.4.5 Itemset 5

![Itemset 5](https://raw.githubusercontent.com/babukanagaraj/DataScience/master/MachineLearning/BasketAnalysis/images/Itemset-5.PNG)

## 5. Conclusion

* **Whole Milk** is the top selling item in the Supermarket.

* Customer had been purchasing Whole Milk when purchased either of the below items,

  * Citrus Fruits
  * Root Vegetables
  * Other Vegetables
  * Yogurt
  * Butter
  * Domestic eggs
  
## 6. Recommendation

* Supermarket can introduce ***promotional discounts*** by clubbing 
  * _Whole Milk_ with its identified frequent associated products.

* Also Supermarket can place the Whole Milk and its associated products in the adjacent shelves so that customers can buy them together.
