## Title
Reverse Train Coaches

## Slug
reverse-train-coaches

## Difficulty
Medium

## Description

A train consists of several connected coaches numbered in order.  
Your task is to reverse the order of coaches between positions `m` and `n`.

`Details:`  
* Positions are 1-indexed.  
* `1 <= m <= n <= number of coaches`.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Coaches 2–4 are reversed.  
New sequence: `1 -> 4 -> 3 -> 2 -> 5`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
Full train reversed.

### 3
#### Input
1  
7  
1 1  

#### Output
7  

#### Explanation
Single coach — no change.

## Input Format
- First line: integer `n` — number of coaches.  
- Second line: `n` integers representing coach numbers.  
- Third line: two integers `m` and `n` — start and end positions.

## Output Format
Print all coach numbers after the reversal.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= coach.no <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
