## Title

Next Code Token

## Slug

next-code-token

## Difficulty

Easy

## Description

You are given a sorted list of lowercase code tokens from a compiler dictionary.  
Find the next token that is lexicographically greater than a target token.  
If none exists, return the first token in the dictionary.

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
- Second line: sorted code tokens.  
- Third line: target token.

## Output Format  

- The next greater token or the first one.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Tokens are lowercase English letters.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays, strings.
