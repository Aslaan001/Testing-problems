## Title
Partition of Strength in the Ember Vault

## Slug
partition-of-strength-in-the-ember-vault

## Difficulty
Hard

## Description

In this scenario, partition of strength in the ember vault must be managed carefully. Each value in the sequence must be divided into two complementary parts so that one forms a non-decreasing pattern while the other forms a non-increasing one. Every split must perfectly reconstruct the original value, and only combinations obeying these constraints are valid. Your task is to count how many such balanced configurations exist, preserving the structural rules while exploring a new thematic setting.

## Examples

### 1

#### Input

3  
2 3 2

#### Output
4

### 2

#### Input

4  
5 5 5 5

#### Output
126

## Input Format

- First line: integer n — the length of the array.  
- Second line: n integers nums[i].  

## Output Format

- Return a single integer — the number of valid balanced split pairs modulo 1e9 + 7.

## Constraints

- 1 ≤ n ≤ 2000  
- 1 ≤ nums[i] ≤ 1000  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

dp combinatorics
