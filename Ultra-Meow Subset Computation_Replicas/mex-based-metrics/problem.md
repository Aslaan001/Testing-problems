## Title
MEX Based Metrics

## Slug
mex-based-metrics

## Difficulty
Hard

## Description
In combinatorial data analysis, mex based metrics arises when evaluating structured collections derived from a fully ordered base set.

A system begins with a canonical sequence containing every integer from 1 through n exactly once.
From this sequence, all possible distinct subsets are considered, representing every potential selection scenario.

For each subset, a numeric characteristic is computed based on identifying missing positive integers.
Specifically, a generalized missing-element function is applied that depends on the size of the subset and the ordering of absent values.

The overall objective is to aggregate this characteristic across every valid subset.
Due to the exponential growth in the number of subsets, the computation must be optimized and the final result reported using modular arithmetic.


## Examples

### 1
#### Input
2  

#### Output
12  

#### Explanation
All distinct subsets of the array {1, 2} are considered, and the corresponding MEX values are summed to obtain the final result.

### 2
#### Input
5  

#### Output
184  

#### Explanation
The computation considers all subsets of the array {1, 2, 3, 4, 5} and sums the required MEX values modulo 10^9 + 7.

## Input Format
- Each test case contains a single integer n — the size of the array consisting of integers from 1 to n.

## Output Format
Return a single integer — the value of MEOW(a) modulo 10^9 + 7 for each test case.

## Constraints 
- 1 ≤ n ≤ 5000  
- The sum of n² over all test cases does not exceed 25 × 10^6  

## Time Limit
2.5 seconds

## Memory Limit
256 megabytes

## Tags
maths, hackwithinfy

## Company
infosys
