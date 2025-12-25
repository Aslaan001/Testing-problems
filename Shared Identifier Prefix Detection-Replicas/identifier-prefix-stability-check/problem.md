## Title

Identifier Prefix Stability Check

## Slug

identifier-prefix-stability-check

## Difficulty

Easy

## Description

A validation component inspects groups of text-based labels to determine structural     commonality.
By comparing characters from the beginning of each text, the component identifies     the longest
contiguous leading sequence present in every identifier. If the labels diverge immediately,     the
result is an empty text, signaling no shared origin.

## Examples

### 1

#### Input

3  
flower  
flow  
flight

#### Output

fl

#### Explanation

All strings start with the prefix `fl`, and no longer common prefix exists.

### 2

#### Input

3  
dog  
dracecar  
dcar

#### Output

d

#### Explanation

There is no common starting prefix shared by all strings.

## Input Format

- First line contains an integer n, the number of strings.
- The next n lines each contain a string.

## Output Format

- Return a single string representing the longest common prefix.
- If no common prefix exists, return an empty string.

## Constraints

- 1 ≤ n ≤ 200  
- 0 ≤ length of each string ≤ 200  
- Each string contains only lowercase English letters if non-empty

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

string

## Company


