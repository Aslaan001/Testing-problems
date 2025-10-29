## Title

Unique Planet ID

## Slug

unique-planet-id

## Difficulty

Medium

## Description

You are mapping planets in a distant galaxy, each with an integer ID.  
Some planets were scanned multiple times.  

Find the `index of the first planet` that appears `exactly once`.  

Return `-1` if all IDs are repeated.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Planet 5 is unique → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Planet 3 appears once → index 4.

## Input Format  

- First line: integer `n` — number of planets scanned.  
- Second line: `n` integers `arr[i]` — planet IDs.

## Output Format  

- A single integer — index of first unique planet, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
