## Title

First Unique Event Code

## Slug

first-unique-event-code

## Difficulty

Medium

## Description

A system records event codes as integers in the sequence they occur.  
Some event codes repeat, while others are one-off.  

Find the `index of the first event code` that appears `exactly once`.  

Return its 0-based index. If no unique event exists, return `-1`.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7   

#### Output
2

#### Explanation

Event code 5 occurs only once → index 2.

### 2

#### Input

5  
1 1 2 2 3     

#### Output

4

#### Explanation

Event code 3 is unique → index 4.

## Input Format  


- First line: integer `n` — number of recorded events.  
- Second line: `n` integers `arr[i]` — event codes.

## Output Format  

- A single integer — the index of the first unique event code, or `-1`.
  

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
