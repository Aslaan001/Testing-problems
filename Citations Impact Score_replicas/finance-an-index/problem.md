## Title
Finance An Index

## Slug
finance-an-index

## Difficulty  
Medium  

## Description

In finance, a an investor's portfolio strength is often measured using the `K-Index`, which reflects both stability and returns.

You are given a sorted array `citations`, where `citations[i]` represents the number of profitable trades for the i-th investment. The `K-Index` is defined as the maximum value `k` such that the an has at least `k` investments, each with at least `k` profitable trades.

## Examples  

### Example 1  

#### Input  
5  
0 1 3 5 6  

#### Output  
3  

#### Explanation  
The researcher has 5 papers with citation counts `[0, 1, 3, 5, 6]`.  
There are 3 papers with at least 3 citations each, so the `K-Index` is `3`.  


### Example 2  

#### Input  
3  
1 2 100  

#### Output  
2  

#### Explanation  
At least 2 papers have 2 or more citations,  
so the `K-Index` is `2`.  



## Input Format  

- The first line contains an integer `n` — the number of papers.  
- The second line contains `n` space-separated integers representing the citation counts in non-decreasing order.  



## Output Format  

Print a single integer — the researcher's `K-Index`.  



## Constraints  

1 ≤ n ≤ 10⁵  
0 ≤ citations[i] ≤ 1000  
citations is sorted in ascending order.  


## Time Limit  

1 second  

## Memory Limit  

512 MB  



## Tags  

binary-search.
