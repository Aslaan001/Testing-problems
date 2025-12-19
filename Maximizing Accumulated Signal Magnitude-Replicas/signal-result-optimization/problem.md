## Title
Signal Result Optimization

## Slug
signal-result-optimization

## Difficulty
Hard

## Description
In high-throughput data processing pipelines, signal result optimization is a common analytical challenge when systems must choose between alternative transformation steps.

A system processes a time-ordered sequence of signed numeric inputs while maintaining a single running accumulator.
At each step, the system may either apply the incoming value directly or apply an additional normalization step that transforms the intermediate result.

Different choices can lead to identical intermediate values but are still considered operationally distinct.
The goal is to determine which combination of choices produces the maximum possible final accumulator value and to count how many distinct operational procedures achieve this maximum.

Due to the potentially exponential number of valid procedures, the final count must be reported using modular arithmetic to ensure computational feasibility.


## Examples

### 1
#### Input
4  
2 -5 3 -3  

#### Output
12  

#### Explanation
The maximum achievable final value is 3.  
There are multiple ways to apply normalization at different positions to reach this value, resulting in 12 distinct procedures.

### 2
#### Input
8  
1 4 3 4 1 4 3 4  

#### Output
256  

#### Explanation
In this case, applying normalization never changes the value of c, so each step has two valid choices, resulting in 2^8 = 256 procedures.

## Input Format
- The first line contains a single integer n — the number of signals.
- The second line contains n integers a1, a2, …, an representing the signal values.

## Output Format
Return a single integer — the number of distinct procedures that result in the maximum possible final value k, modulo 998244353.

## Constraints
- 2 ≤ n ≤ 2 × 10^5  
- −10^9 ≤ ai ≤ 10^9  
- The sum of n over all test cases does not exceed 3 × 10^5  

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
maths, hackwithinfy

## Company
infosys
