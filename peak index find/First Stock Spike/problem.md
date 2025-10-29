## Title

First Stock Spike

## Slug

first-stock-spike

## Difficulty

Medium

## Description

You are analyzing stock prices for consecutive days represented in an array.  
Each element is the stock price for that day.

Find the first index i such that:

- The total of all prices before i is less than price[i].  
- The total of all prices after i is less than price[i].

If no such spike exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Day 1 has a spike: before sum = 1, after sum = 3 → output 1.

### 2

#### Input
5
2 4 3 1 2

#### Output
-1

#### Explanation
No day satisfies the spike rule.

## Input Format
- First line: integer n — number of days.  
- Second line: n integers — stock prices.

## Output Format
- One integer — the first spike index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
