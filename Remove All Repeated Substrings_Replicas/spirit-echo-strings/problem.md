## Title
Spirit Echo Strings

## Slug
spirit-echo-strings

## Difficulty

Medium

## Description
You are given two strings, s and p, representing specialized spirit echo strings.  
Your task is to repeatedly remove occurrences of the substring p from s.

Each time, you must locate the leftmost occurrence of p inside s and delete it.  
Continue this process until s contains no more occurrences of p.

Return the final version of s after all removals.

A substring is defined as a contiguous block of characters.

## Examples

### 1

#### Input
daabcbaabcbc  
abc

#### Output
dab

#### Explanation
The substring abc appears multiple times in s.  
Removing them from left to right produces the final string dab.

### 2

#### Input
axxxxyyyyb  
xy

#### Output
ab

#### Explanation
Repeating the removal of the substring xy eventually reduces the string to ab.

## Input Format

- First line: string s  
- Second line: string p

## Output Format

- Return the resulting string after removing all occurrences of p from s.

## Constraints

- 1 ≤ |s| ≤ 1000  
- 1 ≤ |p| ≤ 1000  
- s and p consist only of lowercase English letters

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

strings, stack, simulation
