## Title
Grinding Volcanic Rock Samples

## Slug
grinding-volcanic-rock-samples

## Difficulty
Medium

## Description
You are given a collection of stones representing grinding volcanic rock samples. In each move, you may smash any two stones: if their weights match, both vanish; otherwise the larger is reduced by the smaller. Your task is to determine the smallest possible final remaining weight after any valid sequence of operations.



### 1

#### Input
6  
2 7 4 1 8 1

#### Output
1

#### Explanation
One optimal sequence of smashes results in ending with a single stone of weight 1.

### 2

#### Input
5  
31 26 33 21 40

#### Output
5

## Input Format

- The first line contains an integer `n`, the number of stones.
- The second line contains `n` space-separated integers representing the stone weights.

## Output Format

Return a single integer — the minimum possible weight of the final stone.

## Constraints

1 ≤ n ≤ 30  
1 ≤ stones[i] ≤ 100  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
dp, knapsack, partition, subset-sum

## Company
hackwithinfy
