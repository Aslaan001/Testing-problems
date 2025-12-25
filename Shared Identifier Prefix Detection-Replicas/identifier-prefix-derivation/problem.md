## Title

Identifier Prefix Derivation

## Slug

identifier-prefix-derivation

## Difficulty

Easy

## Description

A data processing component receives collections of lowercase text labels produced     by various
subsystems. Before performing grouping or optimization steps, the component must     analyze whether
these labels share a common initial segment. The objective is to extract     the longest possible
leading sequence that appears at the start of every text, returning an empty     result when no such
leading sequence can be established.

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


