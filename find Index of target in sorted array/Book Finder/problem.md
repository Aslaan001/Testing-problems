## Title

Book Finder

## Slug

book-finder

## Difficulty

Easy

## Description

In the `Library of Codes`, books are arranged by their `catalog numbers` in `non-decreasing order`.  
Your goal is to locate a specific book with catalog number `k` in the array `books`.  

If found, return its `index`. Otherwise, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
10 20 30 40 50 60  
50

#### Output

4

#### Explanation

The book with catalog number 50 is at index 4.

### 2

#### Input

6  
5 9 13 18 25 35  
14

#### Output

-1

#### Explanation

Catalog number 14 is missing from the shelves.

## Input Format  

- First line: sorted array `books[]`.  
- Second line: integer `k` — the catalog number.

## Output Format  

Return the `index` of the book, or `-1` if not found.

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
