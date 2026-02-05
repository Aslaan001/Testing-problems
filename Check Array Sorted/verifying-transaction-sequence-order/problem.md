## Title

Verifying Transaction Sequence Order

## Slug

verifying-transaction-sequence-order

## Description

In large-scale transaction processing systems, numerical records are often ingested in batches
before downstream validation and analytics are performed.  As part of a routine audit process, you
are given a sequence of integer values representing transaction identifiers captured in arrival
order. Your responsibility is to verify whether this sequence adheres to the system contract that
requires all values to be stored in non-decreasing order. This validation step ensures data
integrity and prevents inconsistencies during reconciliation and reporting. If the sequence respects
the required ordering, the system should confirm compliance; otherwise, it should flag the batch as
invalid.

## Difficulty

Easy

## Examples
### 1

#### Input
5
1 2 3 4 5

#### Output
YES

#### Explanation
The array `[1, 2, 3, 4, 5]` is already sorted in non-decreasing order.


### 2

#### Input
5
5 4 3 2 1

#### Output
NO

#### Explanation
The array is in decreasing order, so it is `not sorted`.

## Input Format
 
- First line contains an integer `n` — the number of elements in the array.  
- Second line contains `n` space-separated integers representing the array.

## Output Format

- Return `"YES"` if the array is sorted in non-decreasing order.  
- Otherwise, Return `"NO"`.

## Constraints

- 1 ≤ n ≤ 10⁶  
- 1 ≤ arr[i] ≤ 10⁶   

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array, sorting.

