## Title
Reverse Robot Sequence

## Slug
reverse-robot-sequence

## Difficulty
Medium

## Description

In a robotic factory, robots are arranged in a queue.  
The engineer wants to reverse their order between two given positions `m` and `n`.

`Details:`  
* Positions are 1-indexed.  
* 1 ≤ m ≤ n ≤ total robots.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Robots at 2–4 reversed → `4 -> 3 -> 2`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
All robots reversed.

### 3
#### Input
1  
8  
1 1  

#### Output
8  

#### Explanation
Only one robot — unchanged.

## Input Format
- First line: integer `n` — number of robots.  
- Second line: `n` integers representing IDs.  
- Third line: two integers `m` and `n` — range to reverse.

## Output Format
Print robot IDs in their new order.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= id <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
