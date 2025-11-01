## Title

Next Cipher Letter

## Slug

next-cipher-letter

## Difficulty

Easy

## Description

A cryptographer has an ordered list of cipher letters.  
Given a target cipher letter, your goal is to find the next greater one in lexicographic order.  
If no greater cipher exists, return the first letter from the list.

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
- Line 2: sorted cipher letters.  
- Line 3: target letter.

## Output Format  

- The next lexicographically greater cipher or the first one.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Letters are lowercase English alphabets.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, strings.
