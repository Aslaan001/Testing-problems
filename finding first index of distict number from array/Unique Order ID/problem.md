## Title

Unique Order ID

## Slug

unique-order-id

## Difficulty

Medium

## Description

An e-commerce system records order IDs.  
Some orders are duplicated due to retries.  

Find the `index of the first unique order ID`.  

Return `-1` if no unique order exists.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Order 5 is unique → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Order 3 unique → index 4.

## Input Format  

- First line: integer `n` — number of orders.  
- Second line: `n` integers `arr[i]` — order IDs.

## Output Format  

- A single integer — index of first unique order, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
