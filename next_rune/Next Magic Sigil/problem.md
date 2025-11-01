## Title

Next Magic Sigil

## Slug

next-magic-sigil

## Difficulty

Easy

## Description

Sigils of power are carved in sorted order by ancient mages.  
Given the list of sigils and a target sigil, determine the next one in sequence.  
If none exists, the magic cycle returns to the first sigil.

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
- Second line: `n` sorted sigils.  
- Third line: target sigil.

## Output Format  

- The next sigil greater than target, or first if none exist.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Sigils are lowercase English letters.

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, strings.
