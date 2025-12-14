## Title
Gallery of Recurrent Colors

## Slug
gallery-of-recurrent-colors

## Difficulty
Hard

## Description
In a setting known as gallery of recurrent colors, a long line of tiles is arranged in a single row, each marked with an integer color.
A traveler moves from left to right by selecting a starting tile and repeatedly jumping forward to later positions.

The visited tiles form a path.
The traveler defines a path as valid only if its total length is divisible by a given integer k.
Such a path can then be divided into consecutive blocks of equal size k, where each block consists of tiles all having the same color.

Among all valid paths, the traveler is interested only in those that achieve the maximum possible length.
Your task is to count how many such maximum-length paths exist, and return the count modulo 1000000007.

## Examples

### 1
#### Input
5 2  
1 2 3 4 5  

#### Output
1

### 2
#### Input
7 2  
1 3 1 3 3 1 3  

#### Output
4

## Input Format
- First line: integers n and k  
- Second line: n integers representing tile colors c1, c2, ..., cn

## Output Format
Return a single integer — the number of maximum-length nice paths modulo 1000000007.

## Constraints
1 ≤ k ≤ n ≤ 100  
1 ≤ ci ≤ n  

## Time Limit
5 seconds

## Memory Limit
256 megabytes

## Tags
dynamic-programming, hackwithinfy

## Company
infosys
