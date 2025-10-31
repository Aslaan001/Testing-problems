## Title

Ranking Position Locator

## Slug

ranking-position-locator

## Difficulty

Medium

## Description

In a competitive exam, scores are stored in ascending order.  
A new participant’s score arrives — determine where it should be placed to maintain sorted rankings.

Use `binary search` to find the correct position quickly.

Return the `0-based index` where the score should be inserted.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

## Input Format  

- First line: integers `n` and `key`.  
- Second line: sorted scores.

## Output Format  

- Integer — insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
