## Title

Next Char in Sequence

## Slug

next-char-in-sequence

## Difficulty

Easy

## Description

You are given a sorted list of characters.  
Find the smallest character that is lexicographically greater than a given target character.  
If no such character exists, wrap around to the first character.

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

- Line 1: integer `n`.  
- Line 2: sorted characters.  
- Line 3: target character.

## Output Format  

- Next character greater than target or the first if none exist.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Lowercase English letters only.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, strings.
