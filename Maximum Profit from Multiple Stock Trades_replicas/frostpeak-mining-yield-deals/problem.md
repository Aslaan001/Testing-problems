## Title  
Frostpeak Mining Yield Deals

## Slug  
frostpeak-mining-yield-deals

## Difficulty  
Medium  

## Description  

You are given an integer array `prices`, where each value represents the fluctuating market value in this fictional trading scenario observed each day.  

You may perform unlimited buy-sell operations, but can hold at most one unit at a time. You may buy and sell on the same day.  

Your task is to determine the maximum total gain achievable from these variations.  

If no profitable opportunities exist, return 0.
## Examples  

### 1  

#### Input  
6  
7 1 5 3 6 4  

#### Output  
7  

#### Explanation  
Buy on day 2 (price = 1) and sell on day 3 (price = 5), profit = 4.  
Buy on day 4 (price = 3) and sell on day 5 (price = 6), profit = 3.  
Total profit = 4 + 3 = 7.  

### 2  

#### Input  
5  
1 2 3 4 5  

#### Output  
4  

#### Explanation  
Buy on day 1 and sell on day 5 for a total profit of 4.  

### 3  

#### Input  
5  
7 6 4 3 1  

#### Output  
0  

#### Explanation  
There are no increasing pairs of prices, so no profitable transaction is possible.  

## Input Format  

- The first line contains an integer `n` — the number of days.  
- The second line contains `n` space-separated integers representing the daily stock prices.  

## Output Format  

Return a single integer — the maximum possible profit achievable through any number of transactions.  

## Constraints  

- 1 ≤ n ≤ 30000  
- 0 ≤ prices[i] ≤ 10000  

## Time Limit  
1 second  

## Memory Limit  
256 MB  

## Tags  
greedy, dynamic-programming, arrays, stock-trading  