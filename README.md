# Customer Segmentation for Promotions - Readme

This project aims to identify categories of customers for potential future promotions for a bank in the U.K. The data used for analysis is collected on 600 customers and is available in the `bankcustomers.csv` file.

## Dataset Description

The dataset consists of the following variables:

- `id`: Customer ID
- `age`: Age in years
- `sex`: Gender (1 for female, 0 for male)
- `region`: Geographic region (1 for inner city, 2 for town, 3 for rural, 4 for suburban)
- `income`: Income in dollars
- `married`: Marital status (1 for married, 0 for not married)
- `children`: Number of children
- `car`: Car ownership (1 for owns a car, 0 for does not own a car)
- `savings`: Savings account (1 for has a savings account, 0 for no savings account)
- `current`: Checking account (1 for has a checking account, 0 for no checking account)
- `mortgage`: Mortgage (1 for has a mortgage, 0 for no mortgage)
- `pep`: Personal Equity Plan (1 for has a personal equity plan, 0 for no personal equity plan)
- `customer ID`: Customer ID (repeated from the `id` column)
- `age in years`: Age in years (repeated from the `age` column)

Note: The `pep` variable represents whether the customer has a personal equity plan and whether tax incentives were provided to promote individual investment in stocks.

## Objective

The objective of this project is to perform customer segmentation based on the provided dataset in order to identify categories of customers for potential future promotions.

## File Structure

- `bankcustomers.csv`: The dataset file containing information on 600 customers.
- `customer_segmentation.ipynb`: Jupyter Notebook containing the code for customer segmentation and analysis.
- `README.md`: This file, providing an overview of the project.

## Usage

To run the customer segmentation analysis and explore the findings, follow these steps:

1. Install the required dependencies (List the required libraries and their versions, if any).
2. Download the `bankcustomers.csv` dataset and place it in the same directory as the `customer_segmentation.ipynb` notebook.
3. Open the `customer_segmentation.ipynb` notebook in Jupyter Notebook or any compatible environment.
4. Run the notebook cells to execute the code and generate insights.
5. Review the analysis results and conclusions presented in the notebook.

## Results

The results of the customer segmentation analysis and any significant findings will be presented in the `customer_segmentation.ipynb` notebook.

## Report

A detailed report of the customer segmentation analysis is available `Clustering.pdf`

## Conclusion

- Based on the analysis, dividing bank customers into five clusters using K-means clustering is the optimal choice.
- Labeling the clusters according to their characteristics and implementing custom promotions for each category can effectively increase bank revenues.
- The identified customer segments include:
  - "Investment-Oriented Inner-City Seniors"
  - "Young but Stable Inner-City Married Adults"
  - "Town Lady with Limited Purchase Power"
  - "Elderly Suburban People"
  - "Affluent Rural Family"
- Hierarchical clustering using Ward linkage also supports dividing customers into five clusters, which provides clear segmentation.
- Utilizing these insights, the bank can tailor promotions and strategies to engage with different customer segments and drive revenue growth.
