## Title

Next Portal Key

## Slug

next-portal-key

## Difficulty

Easy

## Description

In a dungeon of portals, each key is represented by a lowercase rune symbol.  
Given a sorted list of keys and a target key, find the next key that unlocks a higher portal.  
If no greater key exists, the magic wraps and the first key is returned.

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
- Second line: list of sorted keys.  
- Third line: target key.

## Output Format  

- The smallest key greater than target or the first key.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Lowercase letters only.

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays, strings.
