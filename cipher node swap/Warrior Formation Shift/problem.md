## Title
Warrior Formation Shift

## Slug
warrior-formation-shift

## Difficulty
Medium

## Description
A line of warriors stands ready for battle.  
You, the commander, must swap the `kth warrior from the front` with the `kth warrior from the rear` to maintain symmetry in formation.  

Return the adjusted formation.

## Examples
### 1 
#### Input
5  
10 20 30 40 50  
2

#### Output
10 40 30 20 50

#### Explanation
Swapped 2nd warrior from front (`20`) and 2nd from rear (`40`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the updated formation.

## Constraints
- 1 ≤ n ≤ 10^5  
- 1 ≤ k ≤ n  
- 0 ≤ node.val ≤ 100

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, arrays
