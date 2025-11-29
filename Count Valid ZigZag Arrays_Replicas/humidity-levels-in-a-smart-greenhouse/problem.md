## Title
Humidity Levels In A Smart Greenhouse

## Slug
humidity-levels-in-a-smart-greenhouse

## Difficulty
Hard

## Description
You are analyzing humidity levels in a smart greenhouse. Each reading must fall within the inclusive range [l, r]. No two consecutive readings may be identical, and no three consecutive readings may form a strictly increasing or strictly decreasing pattern. Your task is to compute how many valid sequences of length n exist. Return the total count modulo 1000000007.



### 1

#### Input
3 4 5

#### Output
2

### 2

#### Input
3 1 3

#### Output
10

## Input Format

The first line contains three integers n, l, r.

## Output Format

Return a single integer — the total number of valid ZigZag arrays modulo 1000000007.

## Constraints

3 ≤ n ≤ 2000  
1 ≤ l < r ≤ 2000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
dynamic programming, prefix sums

## Company
hackwithinfy
