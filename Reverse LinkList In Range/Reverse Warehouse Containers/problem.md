## Title
Reverse Warehouse Containers

## Slug
reverse-warehouse-containers

## Difficulty
Medium

## Description

In a logistics warehouse, containers are arranged in a line.  
You need to reverse the order of containers between positions `m` and `n`.

`Details:`  
* The positions are 1-indexed.  
* It is guaranteed that `1 <= m <= n <= total containers`.

## Examples

### 1

#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Container sequence: `1 -> 2 -> 3 -> 4 -> 5`.  
Reverse containers between 2 and 4 → `4 -> 3 -> 2`.  
Final: `1 -> 4 -> 3 -> 2 -> 5`.

### 2

#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
All containers reversed.

### 3

#### Input
1  
7  
1 1  

#### Output
7  

#### Explanation
Single container — no change.

## Input Format
- First line: integer `n` — number of containers.  
- Second line: `n` integers representing container IDs.  
- Third line: two integers `m` and `n` — start and end positions for reversal.

## Output Format
Print all container IDs after the partial reversal.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= container.id <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
