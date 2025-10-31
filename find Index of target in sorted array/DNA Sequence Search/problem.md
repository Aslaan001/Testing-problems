## Title

DNA Sequence Search

## Slug

dna-sequence-search

## Difficulty

Easy

## Description

In a bioinformatics lab, DNA sequences are indexed by `genetic strength` values in `non-decreasing order`.  
Find if a sequence with strength `k` exists in the array `dna`.  

Return its `index` if it exists, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
5 10 20 40 60 80  
60

#### Output

4

#### Explanation

The sequence with strength 60 is at index 4.

### 2

#### Input

6  
3 6 9 12 15 18  
8

#### Output

-1

#### Explanation

Sequence with strength 8 is not found.

## Input Format  

- First line: sorted array `dna[]`.  
- Second line: integer `k` — genetic strength.

## Output Format  

Return `index` if found, else `-1`.

## Constraints  

- 1 ≤ n ≤ 1e4  
- 1 ≤ arr[i] ≤ 1e9  
- 0 ≤ k ≤ 1e9  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays.
