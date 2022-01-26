# FinancialEngineering
Repo for the project work in course 42104 Introduction to Financial Engineering at DTU

In this repository one of the projects of the course 42104 is presented. The project is the collaborative work of Jordi Camacho Lopez, Santiago Ribelles Garcia and Kiriakos Tsalkitzidis.

The project is looking into topics such as Sharpe Ratio, portfolio optimization with methods such as the Minimum Spanning Tree and Hierarchical Clustering and conducting other statistical analyses on this financial dataset. It starts off with preparing the dataset by annualizing the weekly returns and calculating the geometrical average return.

The dataset are weekly adjusted returns between January 2012 - August 2021 from a collection of 717 different assets.

The concrete work instructions are shown below. 

## Minimum Spanning Tree.

Start with all the assets available in the Investment Funnel for the entire period. Divide this period into half, where the first half is used for training and the second half for testing.

Q1: Now calculate the Sharpe Ratio for all the assets for the first half (the training set).

Strategy 1:
Q2: Pick up the top 4-5 assets with the highest Sharpe Ratios for the training set.
Q3: Calculate the covariance matrix for these assets.

Strategy 2:
Q4: Pick up the top 200 assets with the highest Sharpe Ratios for the training set.
Q5: Run the Minimum Spanning Tree method on this set a number of times until you have only about 4-5 assets left.
Q6: Calculate the covariance matrix for these assets now and compare with the covariance matrix from strategy 1.

### Compare the performance of the two strategies:
Q7: Calculate average return, std for the two strategies and compare. 
Q8: Calculate and compare the Sharpe ratio for the two strategies. 
Q9: Calculate and compare maximum drawdown for the two strategies.

## Hierarchical Clustering.

Strategy 3:
Continue now with the top 200 assets with the highest Sharpe Ratios for the training set.
Q10: Run the Hierarchical Clustering method on this set to make three clusters.
Q11: Pick the asset with the highest Sharpe ratio from the two smaller clusters.
Q12: Run the Minimum Spanning Three method on the biggest cluster a number of times until you are left with 3-4 assets only.
Q13: Calculate the covariance matrix for these assets now and compare with the covariance matrix from strategy 1 and 2.

Compare the performance of the two strategies:
Q14: Calculate average return, std for the two strategies and compare. 
Q15: Calculate and compare the Sharpe ratio for the two strategies. 
Q16: Calculate and compare maximum drawdown for the two strategies.

## EXTRA QUESTIONS:
The starting point for these questions are the 4-5 assets that you have picked for your portfolios in strategy 2 and 3. So in total you should perform the following statistical analysis for each of these 8-10 assets.

Q17: Draw histograms of returns for each of the assets.
Q18: Draw density function of returns for each of the assets.
Q19: Draw QQ-Plots of returns for each of the assets.
Q20: Perform a Jarque-Bera test for normality of return distributions for each of the assets. 
Q21: Measure and report skewness of returns for each of the assets.
Q22: Measure and report kurtosis of returns for each of the assets.
Q23: For each of the assets, decide and report whether you can accept the return as being normally distributed.
