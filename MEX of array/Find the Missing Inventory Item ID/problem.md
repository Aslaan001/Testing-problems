## Title

Find the Missing Inventory Item ID

## Slug

find-missing-inventory-item

## Difficulty

Easy

## Description

You are managing an inventory system where each item has a unique non-negative ID.  

Some items are currently in stock, and you have a list of their IDs.  
Your task is to find the smallest non-negative item ID that is **not** in stock — the `MEX` of the given list.

## Examples

### 1

#### Input

6  
0 2 1 4 5 7

#### Output
3

#### Explanation
The IDs present are 0, 1, 2, 4, 5, 7.  
The smallest missing ID is `3`.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
All item IDs 0 through 3 are present.  
The next available ID is `4`.

## Input Format

- First line: integer `n` — number of items in stock.  
- Second line: `n` integers `arr[i]` — the item IDs.

## Output Format

- A single integer — the missing item ID.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
