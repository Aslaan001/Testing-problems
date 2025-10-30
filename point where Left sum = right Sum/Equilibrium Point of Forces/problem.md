## Title

Equilibrium Point of Forces

## Slug

equilibrium-point-of-forces

## Difficulty

Easy

## Description

A team of engineers is analyzing the distribution of forces along a beam.  
Each position on the beam is represented by an integer — positive values indicate upward force and negative values indicate downward force.  

Your task is to determine the `smallest index` where the sum of forces on the left equals the sum of forces on the right.  

If no such equilibrium point exists, return `-1`.

## Examples

### 1

#### Input

5
1 7 3 6 5 6 

#### Output
3

#### Explanation
Total sum = 28  
At index 3:  
Left sum = 1 + 7 + 3 = 11  
Right sum = 28 - 11 - 6 = 11  
→ Both sides are balanced → output `3`.

### 2

#### Input

4  
2 2 2 2 

#### Output
-1

#### Explanation
No index produces equal left and right force totals.

## Input Format  

- First line: integer `n` — number of points on the beam.  
- Second line: `n` integers `arr[i]` — force values at each position.

## Output Format  

- A single integer — the smallest index where left sum equals right sum, or `-1` if no such index exists.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr
