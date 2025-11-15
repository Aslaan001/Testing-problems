## Title

Hospital Patient Diagnostic Record

## Slug

hospital-patient-diagnostic-record

## Difficulty

Medium

## Description
In a hospital patient diagnostic record, every record is stored as an integer array `nums`,  
where each number represents a unique item.

The team wants to analyze these items to understand patterns and behaviors.

Your task is to reorder the array according to the following rules:

1. Items that appear less frequently should come first.  
2. If two items have the same frequency, the item with the higher value should come first.

Return the sorted list of items after applying these rules.

## Examples

### 1

#### Input
6  
1 1 2 2 2 3

#### Output
3 1 1 2 2 2

#### Explanation
Product 3 appears once, product 1 appears twice, and product 2 appears three times.  
They are sorted by frequency in increasing order, and by value in decreasing order when frequencies are equal.

### 2

#### Input
5  
2 3 1 3 2

#### Output
1 3 3 2 2

#### Explanation
Both product 2 and product 3 appear twice,  
so they are arranged by their product ID in decreasing order.

### 3

#### Input
9  
-1 1 -6 4 5 -6 1 4 1

#### Output
5 -1 4 4 -6 -6 1 1 1

#### Explanation
Frequencies:  
5 → 1, -1 → 1, 4 → 2, -6 → 2, 1 → 3  
Sorted by frequency ascending and by value descending when tied.

## Input Format

First line contains an integer n — the number of products.  
Second line contains n space-separated integers representing the product IDs.

## Output Format

Return the sorted product IDs according to the rules.

## Constraints

1 ≤ n ≤ 1000  
−100 ≤ nums[i] ≤ 100  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, sorting, frequency, hashmap, retail-analytics
