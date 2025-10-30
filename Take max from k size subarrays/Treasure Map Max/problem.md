## Title
Treasure Map Max

## Slug
treasure-map-max

## Difficulty
Easy

## Description
You have discovered an ancient `Treasure Map` with hidden numeric codes.  
Each number marks the `value of buried gold` in a section of the island.  

Find the `maximum total treasure value` in any `k` consecutive sections.

Return the result as an integer.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Possible sections: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — number of sections.  
- Second line: `n` integers — gold values.  
- Third line: integer `k` — consecutive sections to consider.

## Output Format
One integer — maximum total treasure value.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ value[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
