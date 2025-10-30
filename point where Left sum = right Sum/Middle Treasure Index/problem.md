## Title

Middle Treasure Index

## Slug

middle-treasure-index

## Difficulty

Easy

## Description

While exploring an ancient cave, you find a sequence of treasure chests arranged in a line.  
Each chest can contain gold (`positive`) or a trap (`negative`).  

Your task is to find the `smallest index` where the sum of treasures on the left equals the sum on the right.  
If such a balance point doesn’t exist, return `-1`.

## Examples

### 1

#### Input

5
1 7 3 6 5 6 

#### Output
3

### 2

#### Input

4  
2 2 2 2 

#### Output
-1

## Input Format  

- First line: integer `n`.  
- Second line: `n` integers — treasure values.

## Output Format  

- Single integer — the middle treasure index or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
