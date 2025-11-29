## Title
Data Stream Patterns Forming Up–Down–Up Chunks

## Slug
data-stream-patterns-forming-up–down–up-chunks

## Difficulty
Hard

## Description
You are analyzing a sequence representing data stream patterns forming up–down–up chunks. A trionic subarray is defined as a contiguous segment that strictly increases, then strictly decreases, then strictly increases again, with all transitions occurring at internal indices. Your task is to find the maximum possible sum of any such subarray.



### 1

#### Input
7  
0 -2 -1 -3 0 2 -1

#### Output
-4

### 2

#### Input
4  
1 4 2 7

#### Output
14

## Input Format

The first line contains an integer n.  
The second line contains n integers representing nums.

## Output Format

Return a single integer — the maximum sum of any trionic subarray in nums.

## Constraints

4 ≤ n ≤ 100000  
-10^9 ≤ nums[i] ≤ 10^9

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
two-pointers, dynamic-programming, sliding-window, arrays

## Company
hackwithinfy
