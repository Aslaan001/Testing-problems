## Title

Unique Candidate

## Slug

unique-candidate

## Difficulty

Medium

## Description

In a voting list, each number represents a candidate’s ID.  
Some candidates appear multiple times (duplicate nominations).  

Find the `index of the first candidate` whose ID appears `exactly once`.  

Return `-1` if every candidate appears multiple times.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Candidate 5 appears only once → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Only candidate 3 is unique → index 4.

## Input Format  

- First line: integer `n` — number of IDs.  
- Second line: `n` integers `arr[i]` — candidate IDs.

## Output Format  

- A single integer — index of first unique candidate, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
