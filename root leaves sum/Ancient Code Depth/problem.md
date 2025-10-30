## Title

Ancient Code Depth

## Slug

ancient-code-depth

## Difficulty

Medium

## Description

Hidden beneath ancient ruins lies the `Code Tree` — a digital relic of an extinct civilization.  
Each node stores a numeric code fragment.  
Find the `sum of codes` in the `deepest nodes`, where lost wisdom still whispers.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest nodes `[7, 8]` have total code value `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Deepest fragments `[9, 1, 4, 5]` sum to `19`.

## Input Format  

- First line: integer `n` — number of code fragments  
- Second line: `n` space-separated values (`null` for missing)

## Output Format  

- Return the `sum of deepest code fragments`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, dfs
