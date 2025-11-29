## Title
Purifying Water Currents From Impurity Bands

## Slug
purifying-water-currents-from-impurity-bands

## Difficulty
Medium

## Description
You are working with a sequence representing purifying water currents from impurity bands. You may delete any contiguous segment whose sum is divisible by k, and the array closes after each deletion. You may perform any number of deletions. Your goal is to minimize the final remaining sum.



### 1

#### Input
3  
1 1 1  
2

#### Output
1

#### Explanation
The subarray [1, 1] has sum 2, divisible by 2.  
Removing it leaves [1], whose sum is 1.

### 2

#### Input
5  
3 1 4 1 5  
3

#### Output
5

#### Explanation
Remove the segment [1, 4, 1] since it sums to 6, divisible by 3.  
The array becomes [3, 5].  
Then remove [3], leaving [5].  
Final sum is 5.

## Input Format

The first line contains the integer n.  
The second line contains n integers, representing the array elements.  
The third line contains the integer k.

## Output Format

Return the minimum possible sum of the array after performing deletions.

## Constraints

1 ≤ n ≤ 100000  
1 ≤ nums[i] ≤ 1000000  
1 ≤ k ≤ 100000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
array, prefix-sum, modulo, dynamic-programming

## Company
hackwithinfy
