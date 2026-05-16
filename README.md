# Market Basket Analysis using Apriori Algorithm

## Project Overview

Market Basket Analysis is a data mining technique used to identify associations between products purchased together by customers. This project uses the Apriori Algorithm to discover frequent itemsets and generate association rules from transactional grocery store data.

The main goal of this project is to improve cross-selling strategies, customer recommendations, store layout optimization, and promotional planning.

This project demonstrates how businesses can use customer purchase behavior to make data-driven decisions.


## Objectives

- Identify frequently purchased product combinations
- Discover hidden relationships between products
- Generate association rules using Apriori Algorithm
- Visualize product associations
- Provide actionable business insights


## Dataset

The dataset used in this project contains grocery store transaction records.

Each transaction includes items purchased together by customers.

### Dataset Features

| Column Name | Description |
|-------------|-------------|
| Transaction | Unique transaction ID |
| Item | Product purchased |

### Example

| Transaction | Item |
|-------------|------|
| 1 | Bread |
| 1 | Milk |
| 1 | Butter |
| 2 | Beer |

Dataset Source:
- Kaggle Grocery Dataset


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Mlxtend
- Jupyter Notebook



## Algorithms Used

### Apriori Algorithm

The Apriori Algorithm is used to identify frequent itemsets in transactional datasets.

It works on the principle that:
> If an itemset is frequent, all of its subsets must also be frequent.

The algorithm generates:
- Frequent Itemsets
- Association Rules

### Metrics Used

#### Support
Measures how frequently an itemset appears in the dataset.

#### Confidence
Measures how often items in Y appear in transactions containing X.

#### Lift
Measures the strength of association between products.


## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Transaction Encoding
4. Frequent Itemset Generation
5. Association Rule Mining
6. Data Visualization
7. Business Insights


## Data Preprocessing

The transaction data was converted into basket format using TransactionEncoder.

Example:

| Bread | Milk | Butter |
|------|------|------|
| 1 | 1 | 1 |
| 1 | 0 | 1 |


---

## Visualizations

The project includes:
- Top Frequent Itemsets
- Support vs Confidence Scatter Plot
- Lift-based Association Analysis

These visualizations help understand customer purchasing patterns.



## Business Insights

- Bread and Butter are frequently purchased together.
- Milk and Eggs show strong association.
- Beer and Chips combinations indicate snack purchase behavior.
- High lift products should be placed nearby in stores.


## Business Recommendations

### Cross-Selling
Products frequently bought together should be recommended together.

### Store Layout Optimization
Associated products should be placed close to each other.

### Combo Offers
Businesses can create discount combos for strongly associated products.

### Inventory Planning
Frequently purchased products should maintain higher stock levels.


## Results

The Apriori Algorithm successfully identified frequent itemsets and meaningful association rules from the transaction dataset.

The generated rules can help businesses improve:
- Product recommendations
- Customer experience
- Marketing strategies
- Sales performance


## Future Improvements

- Implement FP-Growth Algorithm
- Build Interactive Dashboard using Streamlit
- Deploy project online
- Add real-time recommendation system
- Compare Apriori and FP-Growth performance


## How to Run the Project

### Step 1
Clone the repository

```bash
git clone YOUR_GITHUB_REPO_LINK
