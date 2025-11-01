## Title
Reverse Troop Formation

## Slug
reverse-troop-formation

## Difficulty
Medium

## Description

A commander lines up soldiers in a formation.  
You are asked to reverse the order of soldiers standing between position `m` and `n`.

`Details:`  
* Positions start from 1.  
* `1 <= m <= n <= total soldiers`.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Formation: `1 -> 2 -> 3 -> 4 -> 5`.  
Reverse positions 2–4 → `4 -> 3 -> 2`.  
Result: `1 -> 4 -> 3 -> 2 -> 5`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
Full reversal of the line.

### 3
#### Input
1  
9  
1 1  

#### Output
9  

#### Explanation
Single soldier, no change.

## Input Format
- First line: integer `n` — number of soldiers.  
- Second line: `n` integers representing soldier IDs.  
- Third line: two integers `m` and `n` — the start and end of the reversal range.

## Output Format
Print all soldier IDs in the new order.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= soldier.id <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
