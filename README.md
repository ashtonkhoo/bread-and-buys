# Market Basket Analysis on Bakery Dataset
This repository contains resources for a Market Basket Analysis project utilizing the Apriori Algorithm. The analysis is based on an open-source [Bakery dataset](https://www.kaggle.com/datasets/akashdeepkuila/bakery/data) available on Kaggle. Association rule mining is employed to identify patterns and relationships between items that are frequently purchased together. These insights can be leveraged to enhance targeted marketing strategies, improve product placement, and optimize inventory management.

# Objective
The primary goal of this study was to identify item combinations that are frequently purchased together, with a focus on variations across different times of the day, and days of the week.

# Key Processes
* **Data Preprocessing:** Cleaning the data, grouping together observations with same transaction number and date/time, transforming the data into a set of transactions.
* **Exploratory Data Analysis:** Generating summary statistics, Finding and Inspecting Frequent Itemsets, Visualizating Association Rules to uncover patters in purchasing behaviour.
* **Modeling:** Mining Association Rules using Apriori Algorithm, and Inspecting the Rules based on measures like Support, Confidence, and Lift.

## Installation
Follow these steps to set up the project locally.

### 1. Clone the Repository
```bash
git clone https://github.com/ashtonkhoo/bread-and-buys.git
cd bread-and-buys
```

### 2. Install libraries
```bash
pip install -r requirements.txt
```

## Contributions
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.
