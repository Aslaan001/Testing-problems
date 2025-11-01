## Title
Order Cargo Shipment

## Slug
order-cargo-shipment

## Difficulty
Medium

## Description

A shipping company maintains cargo weights in a linked list.  
The weights are unsorted.  
Sort the cargo weights in ascending order to prepare them for shipment.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
The cargo weights are ordered from lightest to heaviest.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
All shipments are sorted properly by weight.

## Input Format
- Line 1: integer `n`.  
- Line 2: `n` integers representing cargo weights.

## Output Format
Sorted weights printed in ascending order.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
