## Title

Common Token Head Extraction

## Slug

common-token-head-extraction

## Difficulty

Easy

## Description

For optimization and lookup acceleration, a backend module must extract a shared leading     segment
from a set of labels. This operation involves scanning the texts from left to     right and stopping
at the first position where any identifier differs. The resulting leading sequence,     if any,
captures the common starting pattern among all inputs.

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


