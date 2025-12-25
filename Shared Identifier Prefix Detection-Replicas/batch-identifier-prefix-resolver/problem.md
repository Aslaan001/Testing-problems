## Title

Batch Identifier Prefix Resolver

## Slug

batch-identifier-prefix-resolver

## Difficulty

Easy

## Description

In identifier management workflows, consistency at the beginning of names often indicates     shared
ownership or categorization. Given a list of textual labels, the system evaluates     their starting
characters collectively to compute the maximum-length leading sequence that all entries     share.
This leading sequence serves as a normalization artifact for downstream processes.

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


