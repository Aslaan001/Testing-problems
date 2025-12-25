## Title

Shared Label Head Computation

## Slug

shared-label-head-computation

## Difficulty

Easy

## Description

In large-scale backend systems, textual labels are generated independently by     multiple
components yet are often expected to follow consistent naming schemes. To support     efficient
routing, indexing, and validation, the system must determine the longest starting     sequence of
characters that is common across all labels in a batch. This shared leading sequence     represents
the maximal common structure present at the beginning of every identifier and may     be empty if no
alignment exists.

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


