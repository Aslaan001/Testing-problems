## Title

Next Planet Signal

## Slug

next-planet-signal

## Difficulty

Easy

## Description

An interstellar signal array receives alphabetic signals sorted lexicographically.  
Given a target signal, find the next strongest signal (next lexicographical letter).  
If none exists, return the first signal in the list.

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
- Second line: list of sorted signal letters.  
- Third line: target signal.

## Output Format  

- The next lexicographically greater signal or the first one.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Lowercase English letters.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, strings.
