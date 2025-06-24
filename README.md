# Apriori Algorithm with Apyori - Market Basket Analysis

This project is part of a university assignment and demonstrates the implementation of the **Apriori algorithm** using the **Apyori** library in Python. The goal is to identify frequent itemsets and generate association rules from a transactional dataset, commonly used in market basket analysis.

## Objective

The main objective is to discover patterns of items frequently purchased together, supporting strategic decisions in the retail sector. This is achieved by applying data mining techniques to a set of simulated transactions.

##  Technologies

* Python 3.x
* [Apyori](https://pypi.org/project/apyori/) library
* Jupyter Notebook (optional, for running and visualizing the results)

## What the project does

* Loads and processes transaction data
* Applies the Apriori algorithm using the Apyori library
* Extracts association rules based on **support**, **confidence**, and **lift**
* Displays the most relevant rules for decision-making

## How to run

1. Install the apyori library (if needed):

   ```
   pip install apyori
   ```

2. Run the script or notebook and observe the generated rules.

## Notes

* The dataset used is a simple example representing market transactions.
* The rules generated can be interpreted to guide marketing or product placement strategies.
