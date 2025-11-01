## Title

Next Letter

## Slug

next-letter

## Difficulty

Easy

## Description

You are given a sorted list of lowercase letters and a target letter.  
Your task is to find the smallest letter that is lexicographically greater than the target.  
If no such letter exists, return the first letter in the list.

## Examples

### 1

#### Input

3
c f j
a

#### Output

c

#### Explanation

The next letter after `'a'` is `'c'`.

### 2

#### Input

3
c f j
c

#### Output

f

#### Explanation

The next letter after `'c'` is `'f'`.

## Input Format  

- First line: integer `n`.  
- Second line: `n` space-separated lowercase letters (sorted).  
- Third line: target letter.

## Output Format  

- The next lexicographically greater letter, or the first if none exist.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Letters are lowercase English alphabets (`a`–`z`).  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays, strings.
