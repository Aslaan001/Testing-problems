## Title
Reverse Galactic Node Chain

## Slug
reverse-galactic-node-chain

## Difficulty
Medium

## Description

In the Milky System, stars are connected through an energy chain.  
Given the `head` of this galactic chain and two integers `m` and `n`, reverse the order of stars between position `m` and position `n`.

`Details:`  
* Positions are 1-indexed (i.e., the first star is at position `1`).  
* It is guaranteed that `1 <= m <= n <= total stars`.

## Examples

### 1

#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
The chain is: `1 -> 2 -> 3 -> 4 -> 5`.  
We reverse the part between 2 and 4: `2 -> 3 -> 4` → `4 -> 3 -> 2`.  
Final chain: `1 -> 4 -> 3 -> 2 -> 5`.

### 2

#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
The full star chain reversed becomes: `3 -> 2 -> 1`.

### 3

#### Input
1  
9  
1 1  

#### Output
9  

#### Explanation
Only one star exists, so no change occurs.

## Input Format
-   First line: integer `n` — total number of stars.
-   Second line: `n` integers representing brightness levels.
-   Third line: two integers `m` and `n` — start and end of the reversal range.

## Output Format
Print all star values of the modified chain in one line separated by spaces.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= node.val <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
