## Title
Inventory Adjustment Harmonization Strategy

## Slug
inventory-adjustment-harmonization-strategy

## Difficulty  
Easy  

## Description

In a enterprise supply chain platform, inventory adjustment values are recorded sequentially as part of routine operational updates.

For reporting and downstream processing, these adjustment values must eventually form a non decreasing sequence, ensuring that no adjustment reflects a decrease relative to the previous recorded value.

To enforce this ordering requirement, the system allows a controlled merge operation. During such an operation, the system identifies the adjacent pair of values with the smallest combined total. If multiple pairs share the same minimum combined value, the leftmost pair is selected to maintain deterministic behavior.

The selected pair is replaced by a single value equal to their sum, effectively reducing the sequence length by one. Each such consolidation counts as one operational step.

The objective is to determine the minimum number of merge operations required to transform the original adjustment sequence into a non decreasing sequence while strictly following the defined merge selection rules.
## Examples  

### 1  

#### Input  
4  
5 2 3 1  

#### Output  
2  

#### Explanation  

- The adjacent pair (3, 1) has the minimum sum of 4 → array becomes [5, 2, 4]  
- The adjacent pair (2, 4) has the minimum sum of 6 → array becomes [5, 6]  
- The array is now non-decreasing after 2 operations  

### 2  

#### Input  
3  
1 2 2  

#### Output  
0  

#### Explanation  

The array is already non-decreasing, so no operations are needed.

## Input Format  

- The first line contains an integer n — the length of the array  
- The second line contains n space-separated integers representing the array values  

## Output Format  

Return a single integer representing the minimum number of merge operations required.

## Constraints  

1 ≤ n ≤ 50  
-1000 ≤ nums[i] ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.