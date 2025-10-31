## Title

Music Note Pairing

## Slug

music-note-pairing

## Difficulty

Medium

## Description

A composer has written a list of musical notes, each represented by an integer frequency.  
He wants to combine them into pairs so that the `sum of frequencies` in every pair is divisible by a given rhythm number `k`.

Return `"YES"` if such pairing is possible, otherwise return `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9, 3)` and `(7, 5)` make sums divisible by `6`.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- First line: integer `n`.  
- Second line: `n` integers representing the notes.  
- Third line: integer `k`.

## Output Format

- Print `"YES"` if the notes can be paired, otherwise `"NO"`.

## Constraints

- 1 ≤ n ≤ 10⁵  
- 1 ≤ arr[i] ≤ 10⁹  
- 1 ≤ k ≤ 10⁹  
- `n` is even  

## Time Limit

1 second  

## Memory Limit

512 MB  

## Tags

arrays, sorting.
