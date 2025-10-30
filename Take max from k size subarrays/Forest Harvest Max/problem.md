## Title
Forest Harvest Max

## Slug
forest-harvest-max

## Difficulty
Easy

## Description
You are in a magical forest where each tree produces a number of fruits daily.  
Your task is to find the `maximum number of fruits` collected from any `k` consecutive trees`.

Return the maximum total fruits gathered.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Consecutive tree yields: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — total trees.  
- Second line: `n` integers — fruits per tree.  
- Third line: integer `k` — consecutive trees.

## Output Format
Single integer — maximum fruit count.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ fruits[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
