## Title

Move Weakest Warrior First

## Slug

move-weakest-warrior-first

## Difficulty

Easy

## Description

In a lineup of warriors, each has a strength value represented as an integer.  
You must bring the `weakest warrior` (the one with the smallest strength) to the front of the line by swapping it with the first position.  

If the weakest warrior is already first, the formation remains unchanged.

## Examples

### 1

#### Input

5
5 3 4 2 1 

#### Output
1 3 4 2 5

#### Explanation
The weakest warrior (`1`) moves to the front by swapping with `5`.

### 2

#### Input

4
2 1 3 4 

#### Output

1 2 3 4

#### Explanation
`1` swaps with the first element `2` to lead the lineup.

## Input Format  

- First line: integer `n`.  
- Second line: `n` integers — strengths of warriors.

## Output Format  

- The updated lineup after swapping.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, swapping.
