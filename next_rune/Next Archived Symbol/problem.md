## Title

Next Archived Symbol

## Slug

next-archived-symbol

## Difficulty

Easy

## Description

You are working in a vast digital archive of ancient symbols.  
The symbols are sorted alphabetically.  
Given a target symbol, find the smallest symbol that comes after it lexicographically.  
If no greater symbol exists, wrap around and return the first one in the archive.

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

- First line: integer `n` — number of symbols.  
- Second line: `n` sorted symbols.  
- Third line: target symbol.

## Output Format  

- The smallest symbol greater than target, or first symbol if none exist.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Symbols are lowercase English letters.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, strings, arrays.
