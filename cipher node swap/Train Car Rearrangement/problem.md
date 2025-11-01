## Title
Train Car Rearrangement

## Slug
train-car-rearrangement

## Difficulty
Medium

## Description
A cargo train is represented as a chain of cars, each containing a shipment ID.  
Due to imbalance, the railway engineer must swap the `kth car from the front` with the `kth car from the rear`.  

Return the `updated train order` after the swap.

## Examples
### 1 
#### Input
5  
1 2 3 4 5  
2

#### Output
1 4 3 2 5

#### Explanation
Swapped 2nd car from front (`2`) with 2nd car from back (`4`).

## Input Format
- First line: integer `n` — number of train cars.  
- Second line: `n` integers — IDs of cars.  
- Third line: integer `k`.

## Output Format
Return the reordered train cars.

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
