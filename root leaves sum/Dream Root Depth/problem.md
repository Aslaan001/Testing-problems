## Title

Dream Root Depth

## Slug

dream-root-depth

## Difficulty

Medium

## Description

In the dreamscape, ideas sprout through the `Tree of Thought`.  
Each node holds the intensity of imagination.  
Your task is to calculate the `sum of intensities` of the `deepest dreams` rooted in the subconscious.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest dreams `[7, 8]` carry total intensity `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Dream roots `[9, 1, 4, 5]` hold total power `19`.

## Input Format  

- First line: integer `n` — number of dream nodes  
- Second line: `n` space-separated level-order traversal (`null` for missing)

## Output Format  

- Return the `sum of deepest dream intensities`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, recursion
