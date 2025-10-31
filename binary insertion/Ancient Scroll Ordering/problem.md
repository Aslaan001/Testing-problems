## Title

Ancient Scroll Ordering

## Slug

ancient-scroll-ordering

## Difficulty

Medium

## Description

An archivist maintains a sorted collection of ancient scrolls numbered by age.  
A new scroll has been found — find the correct position where it should be placed so the order remains sorted.

Use `binary search` to efficiently find the index.

Return the `0-based index` where the scroll belongs.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

## Input Format  

- First line: two integers `n` and `key`.  
- Second line: sorted scroll numbers.

## Output Format  

- Integer — insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
