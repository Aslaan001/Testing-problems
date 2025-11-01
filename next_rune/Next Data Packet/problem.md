## Title

Next Data Packet

## Slug

next-data-packet

## Difficulty

Easy

## Description

A communication server maintains packets labeled with lowercase letters in sorted order.  
Given a target packet ID, find the smallest packet label greater than it.  
If no greater packet exists, return the first packet ID.

## Examples

### 1

#### Input

3
c f j
a

#### Output

c

### 2

#### Input

3
c f j
c

#### Output

f

## Input Format  

- First line: integer `n`.  
- Second line: `n` sorted packet labels.  
- Third line: target label.

## Output Format  

- The next packet label or the first if none exist.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Lowercase letters only.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays, strings.
