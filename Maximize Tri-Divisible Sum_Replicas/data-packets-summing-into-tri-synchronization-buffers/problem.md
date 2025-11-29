## Title
Data Packets Summing Into Tri-Synchronization Buffers

## Slug
data-packets-summing-into-tri-synchronization-buffers

## Difficulty
Medium

## Description
You are working with a collection of values representing data packets summing into tri-synchronization buffers. Your task is to choose a subset whose total sum is divisible by 3, and among all such subsets, you must maximize the total sum. If no non-empty subset works, the empty subset with sum 0 is valid.



### 1

#### Input
5  
3 6 5 1 8

#### Output
18

#### Explanation
A possible optimal subset is [3, 6, 1, 8], which sums to 18.  
This is divisible by 3 and is the maximum possible sum.

### 2

#### Input
1  
4

#### Output
0

#### Explanation
4 alone is not divisible by 3.  
Thus, the empty subset gives sum 0.

### 3

#### Input
5  
1 2 3 4 4

#### Output
12

#### Explanation
Selecting [1, 3, 4, 4] yields a total of 12, which is divisible by 3.

## Input Format

- The first line contains an integer n.  
- The second line contains n space-separated integers.

## Output Format

Return a single integer: the maximum sum divisible by 3.

## Constraints

1 ≤ n ≤ 40000  
1 ≤ nums[i] ≤ 10000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
array, greedy, dynamic-programming, modulo


## Company
hackwithinfy