## Title
Travelers Descending Floating Islands Linked By Jump Paths

## Slug
travelers-descending-floating-islands-linked-by-jump-paths

## Difficulty
Hard

## Description
You are navigating a sequence of platforms representing travelers descending floating islands linked by jump paths. You may jump left or right up to distance d, but only to strictly lower platforms, and only if all platforms between the jump endpoints are also lower than the starting one. Your goal is to determine the maximum number of distinct platforms that can be visited.



### 1

#### Input
11  
6 4 14 6 8 13 9 7 10 6 12  
2

#### Output
4

### 2

#### Input
5  
3 3 3 3 3  
3

#### Output
1

### 3

#### Input
7  
7 6 5 4 3 2 1  
1

#### Output
7

## Input Format

- The first line contains an integer `n` — the length of the array.
- The second line contains `n` space-separated integers (`arr[i]`).
- The third line contains the integer `d`.

## Output Format

Return a single integer — the `maximum number of reachable indices`.

## Constraints

1 ≤ n ≤ 1000  
1 ≤ arr[i] ≤ 100000  
1 ≤ d ≤ n  

## Time Limit
`1 second`

## Memory Limit
`512 MB`

## Tags
dp, dfs, graph, monotonic, jumps


## Company
hackwithinfy