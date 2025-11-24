## Title
Find Star Shards Pair

## Slug
find-star-shards-pair

## Difficulty

Easy

## Description
You are given an array of integers and a target value.  
Your task is to find two different positions in the array such that the two selected star shards combine to match the target value.

Each input is guaranteed to have exactly one valid matching pair.  
The order of the two returned indices does not matter.

The two chosen indices must refer to distinct positions.

## Examples

### 1

#### Input
4  
2 7 11 15  
9

#### Output
0 1

#### Explanation
The values at indices 0 and 1 sum to 9.

### 2

#### Input
3  
3 2 4  
6

#### Output
1 2

### 3

#### Input
2  
3 3  
6

#### Output
0 1

## Input Format

- First line: integer n — number of elements  
- Second line: n integers representing the array  
- Third line: integer target — the required sum

## Output Format

- Two integers representing indices of the elements that sum to the target

## Constraints

- 2 ≤ n ≤ 10^4  
- −10^9 ≤ nums[i] ≤ 10^9  
- −10^9 ≤ target ≤ 10^9  
- Exactly one valid pair always exists

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

hashing, arrays, two-pointer, search
