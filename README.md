# Project Description:

This project focuses on comparing the performance of two different strategies, Random Selection, and Thompson Sampling, for the selection of advertisements in a simulation environment. The goal is to demonstrate how Thompson Sampling, a Bayesian approach, outperforms random selection over time by minimizing regrets and optimizing the selection process.

# Actions Taken:

### Importing Libraries and Defining Simulation Environment:
Imported necessary libraries including numpy, pandas, seaborn, and set up the simulation environment with a predefined dataset from 'Ads_CTR_Optimisation.csv'.

### Simulation Environment Setup:

1) Loaded the dataset and initialized variables for the number of rounds (N) and the number of ads (d).

2) Created two strategies for ad selection: Random Selection and Thompson Sampling.

3) Tracked the number of selections and rewards for each strategy.

### Performance Evaluation:

1) Calculated the amount difference and percentage difference in total rewards between Thompson Sampling and Random Selection.

2) Plotted histograms comparing the count of strategy selections for both methods.

![Strategy_selection_count_comparison.png](https://github.com/Kaustav1111/Advertising-Strategy-Intelligence-for-E_Commerce-website-using-Thompson-Sampling/blob/main/Strategy_selection_count_comparison.png)

### Strategy Selection Visualizations:

Visualized the ad selection pattern for both strategies over rounds, highlighting the randomness in random selection and the optimized pattern in Thompson Sampling.
![Strategy_selection_through_rounds_comparison.png](https://github.com/Kaustav1111/Advertising-Strategy-Intelligence-for-E_Commerce-website-using-Thompson-Sampling/blob/main/Strategy_selection_through_rounds_comparison.png)

### Regret Curves:

Computed and visualized regret curves for both Random Selection and Thompson Sampling over the course of the simulation.

![random.png](https://github.com/Kaustav1111/Advertising-Strategy-Intelligence-for-E_Commerce-website-using-Thompson-Sampling/blob/main/random.png) ![regret_curve_thompson.png](https://github.com/Kaustav1111/Advertising-Strategy-Intelligence-for-E_Commerce-website-using-Thompson-Sampling/blob/main/regret_curve_thompson.png)

### Performance Metrics:

![result_diff.png](https://github.com/Kaustav1111/Advertising-Strategy-Intelligence-for-E_Commerce-website-using-Thompson-Sampling/blob/main/result_diff.png)


This project effectively demonstrates the superiority of Thompson Sampling over Random Selection in optimizing ad strategy selection, resulting in higher rewards and lower regrets. The visualizations and performance metrics provide insights into the effectiveness of these strategies in a simulated environment.



