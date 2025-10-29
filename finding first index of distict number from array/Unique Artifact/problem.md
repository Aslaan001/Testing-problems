## Title

Unique Artifact

## Slug

unique-artifact

## Difficulty

Medium

## Description

An archaeologist discovers artifacts represented by integers.  
Some artifact IDs repeat due to replicas, while others are unique.  

Find the `index of the first unique artifact`.  

If all are duplicates, return `-1`.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Artifact 5 is unique → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Artifact 3 is unique → index 4.

## Input Format  

- First line: integer `n` — number of artifacts.  
- Second line: `n` integers `arr[i]` — artifact IDs.

## Output Format  

- A single integer — index of first unique artifact, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
