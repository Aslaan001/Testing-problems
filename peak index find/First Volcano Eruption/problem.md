## Title

First Volcano Eruption

## Slug

first-volcano-eruption

## Difficulty

Medium

## Description

Volcanologists have measured eruption strengths of several volcanoes in sequence.  
Your goal is to find the first volcano that erupts more strongly than the combined power of all others before and after it.

Find the smallest index i where:

- The sum before i is less than arr[i].  
- The sum after i is less than arr[i].

If no volcano fits this condition, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Volcano at index 1 dominates all others.

### 2

#### Input
5
2 2 3 4 1

#### Output
-1

#### Explanation
No eruption strong enough to dominate both sides.

## Input Format
- First line: integer n — number of volcanoes.  
- Second line: n integers — eruption strengths.

## Output Format
- One integer — the first dominant eruption index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
