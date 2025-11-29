## Title
Time‑Travelers Ranked By Paradox Stability

## Slug
time‑travelers-ranked-by-paradox-stability

## Difficulty
Medium

## Description
You are given a lineup of time‑travelers ranked by paradox stability. Each one has a unique rating. Your task is to count how many valid trios can be formed such that their ratings strictly increase or strictly decrease when chosen in order (i < j < k). Return the total number of such valid trios.



### 1
#### Input
5  
2 5 3 4 1

#### Output
3

#### Explanation
Valid teams are:  
(2, 3, 4), (5, 4, 1), (5, 3, 1)

### 2
#### Input
3  
2 1 3

#### Output
0

### 3
#### Input
4  
1 2 3 4

#### Output
4

## Input Format
- The first line contains an integer n  
- The second line contains n space-separated unique integers representing ratings

## Output Format
Return a single integer — the total number of valid teams.

## Constraints
3 ≤ n ≤ 1000  
1 ≤ rating[i] ≤ 100000  
All ratings are unique

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
array, counting, combinatorics, dp

## Company
hackwithinfy