## Title
Log Verification Metrics

## Slug
log-verification-metrics

## Difficulty
Hard

## Description
In large-scale data analysis environments, log verification metrics is a crucial step in ensuring the correctness and trustworthiness of recorded information.

A system processes sequential records where each entry is represented by a positive integer value.
To assess data integrity, the system evaluates ordered pairs of records and derives a combined metric from each selected pair.

For any two records at positions i and j with i ≤ j, a derived value is computed using the least common multiple of their numeric representations.
This derived value is then checked against a strict classification rule that determines whether it satisfies an integrity criterion based on its prime factorization.

Each dataset must be analyzed independently, and every ordered pair that satisfies the integrity condition contributes to the final count.
The objective is to accurately compute how many such valid pairs exist while adhering to performance constraints imposed by large input sizes.


## Examples

### 1
#### Input
4  
2 2 3 4  

#### Output
5 

#### Explanation
There are 5 ordered index pairs (i, j) such that i ≤ j and the least common multiple of the selected values is a semi-prime number.

### 2
#### Input
6  
2 2 3 4 5 6  

#### Output
12  

#### Explanation
Several pairs of log entries produce semi-prime values when their least common multiple is computed.

## Input Format
- The first line contains an integer n — the number of log entries.
- The second line contains n integers a1, a2, …, an representing the encoded log values.

## Output Format
Return a single integer — the number of ordered pairs (i, j) such that i ≤ j and lcm(ai, aj) is a semi-prime number.

## Constraints  
- 2 ≤ n ≤ 2 × 10^5  
- 2 ≤ ai ≤ n  
- The sum of n over all test cases does not exceed 2 × 10^5  

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
maths, hackwithinfy

## Company
infosys
