## Title

Planet Age Search

## Slug

planet-age-search

## Difficulty

Easy

## Description

In a planetary database, the ages of discovered planets are stored in ascending order.  
You must check if a planet with age `k` exists.  

Return its `index` if it does, or `-1` otherwise.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
100 200 300 400 500  
400

#### Output

3

#### Explanation

Planet with age 400 is found at index 3.

### 2

#### Input

5  
50 100 150 200 250  
275

#### Output

-1

#### Explanation

No planet of age 275 found.

## Input Format  

- First line: sorted array `planets[]`.  
- Second line: integer `k` — target age.

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
