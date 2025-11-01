## Title
Reverse DNA Segment

## Slug
reverse-dna-segment

## Difficulty
Medium

## Description

A DNA strand is represented as a sequence of values.  
Given the strand and two indices `m` and `n`, reverse the order of elements between these positions.

`Details:`  
* Positions are 1-indexed.  
* 1 ≤ m ≤ n ≤ length of strand.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Reversing section 2–4 gives `1 -> 4 -> 3 -> 2 -> 5`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
Entire strand reversed.

### 3
#### Input
1  
6  
1 1  

#### Output
6  

#### Explanation
Single element — unchanged.

## Input Format
- First line: integer `n` — number of elements in the DNA strand.  
- Second line: `n` integers.  
- Third line: two integers `m` and `n` — range to reverse.

## Output Format
Print the DNA strand after reversal.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= base.value <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
