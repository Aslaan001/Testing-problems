## Title
Price Comparison Ratio Selection

## Slug
price-comparison-ratio-selection

## Difficulty  
Medium  

## Description

In a benchmark comparison module, a set of reference price values is maintained for comparative analysis. These values are stored in a strictly increasing order, beginning with the baseline value of 1 followed by prime numbers.

Analysts derive comparative indicators by forming ratios between two values in the list, where the numerator is chosen from an earlier position and the denominator from a later position. Each ratio represents a relative price relationship used for ranking and decision support.

All valid ratios generated from the list are conceptually sorted in ascending order. This ordered collection allows analysts to reason about proportional differences between benchmarks in a structured manner.

Given the ordered list of values and a target rank k, the task is to identify the ratio that appears at the k-th position in this sorted order. The result must be reported using the original numerator and denominator values that form this ratio.

This operation must be performed efficiently due to the potentially large number of possible ratios, while preserving numerical accuracy and respecting the sorted structure of the input data.
## Examples  

### 1  

#### Input  
4  
1 2 3 5  
3  

#### Output  
2 5  

#### Explanation  

All possible ratios in ascending order are:  
1/5, 1/3, 2/5, 1/2, 3/5, 2/3  

The 3rd smallest ratio is 2/5.

### 2  

#### Input  
2  
1 7  
1  

#### Output  
1 7  

## Input Format  

- The first line contains an integer n — the length of the array  
- The second line contains n space-separated integers representing the array arr  
- The third line contains an integer k  

## Output Format  

Return two integers — the numerator and denominator of the k-th smallest ratio.

## Constraints  

2 ≤ n ≤ 1000  
1 ≤ arr[i] ≤ 30000  
arr[0] = 1  
arr[i] is prime for i > 0  
All elements of arr are unique and sorted  
1 ≤ k ≤ n × (n − 1) / 2  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

priority-queue.