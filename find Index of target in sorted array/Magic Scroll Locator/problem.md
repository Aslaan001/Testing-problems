## Title

Magic Scroll Locator

## Slug

magic-scroll-locator

## Difficulty

Easy

## Description

In the ancient library of `Mystos`, enchanted scrolls are placed in shelves sorted by their `power index` in `non-decreasing order`.  
You, the `Arcane Scribe`, must locate a scroll with a specific power `k` within the array `scrolls`.  

If the scroll exists, return its `index`.  
If not, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
4 8 12 16 20 24  
16

#### Output

3

#### Explanation

The scroll with power 16 is located at index 3.

### 2

#### Input

6  
2 5 9 11 15 19  
10

#### Output

-1

#### Explanation

There is no scroll with power 10 in the library.

## Input Format  

- First line: sorted array `scrolls[]`.  
- Second line: integer `k` — the power of the target scroll.

## Output Format  

Return a single integer — the `index` of the target scroll. If not found, return `-1`.

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
