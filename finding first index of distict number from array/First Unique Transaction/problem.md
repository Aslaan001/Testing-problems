## Title

First Unique Transaction

## Slug

first-unique-transaction

## Difficulty

Medium

## Description

A ledger records transaction types as integers in chronological order.  
Some transaction types occur multiple times, while others happen only once.  

Your task is to find the `index of the first transaction type` that appears `exactly once`.  

Return the 0-based index of this transaction type. If no unique transaction exists, return `-1`. 


## Examples

### 1

#### Input

6  
2 3 5 3 2 7   

#### Output
2

#### Explanation

- Transaction types: 2, 3, 5, 3, 2, 7  
- 5 appears once → first unique at index 2.

### 2

#### Input

5  
1 1 2 2 3     

#### Output

4

#### Explanation

- 3 appears once → index 4.

## Input Format  


- First line: integer `n` — number of transactions.  
- Second line: `n` integers `arr[i]` — transaction type IDs.

## Output Format  

- A single integer — the index of the first unique transaction type, or `-1`.
  

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
