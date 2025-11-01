## Title
Reverse Data Packets

## Slug
reverse-data-packets

## Difficulty
Medium

## Description

A stream of data packets travels through a network.  
Reverse the order of packets between positions `m` and `n`.

`Details:`  
* Positions are 1-indexed.  
* 1 ≤ m ≤ n ≤ total packets.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Packets 2–4 reversed → `4 -> 3 -> 2`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
Full packet stream reversed.

### 3
#### Input
1  
5  
1 1  

#### Output
5  

#### Explanation
Only one packet, no change.

## Input Format
- First line: integer `n` — number of packets.  
- Second line: `n` integers representing packet IDs.  
- Third line: two integers `m` and `n` — start and end positions.

## Output Format
Print packet IDs after reversal.

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
