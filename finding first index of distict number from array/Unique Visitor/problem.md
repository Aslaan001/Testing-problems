## Title

Unique Visitor

## Slug

unique-visitor

## Difficulty

Medium

## Description

A website logs visitors using integer IDs.  
Some visitors return multiple times.  

Find the `index of the first visitor` who visited only once.  

Return `-1` if all visitors are repeated.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Visitor 5 is unique → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Visitor 3 is unique → index 4.

## Input Format  

- First line: integer `n` — number of visits logged.  
- Second line: `n` integers `arr[i]` — visitor IDs.

## Output Format  

- A single integer — index of first unique visitor, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
