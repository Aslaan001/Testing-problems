## Title
Shattering Square Ethereal Anchors

## Slug
shattering-square-ethereal-anchors

## Difficulty
Hard

## Description
You are given a pile of stones representing shattering square ethereal anchors. On each turn, a player removes a positive number of stones equal to a perfect square. Players alternate and play optimally. Determine if the first player can guarantee a win.



### 1
#### Input
1

#### Output
true

#### Explanation
The first player removes 1 stone and wins immediately.

### 2
#### Input
2

#### Output
false

#### Explanation
The first player removes 1 stone, leaving 1 for the opponent, who wins.

### 3
#### Input
4

#### Output
true

#### Explanation
The first player removes 4 stones in one move.

## Input Format
- A single integer `n` representing the initial number of stones.

## Output Format
Return `YES` or `NO` depending on whether the first player can guarantee a win.

## Constraints
1 ≤ n ≤ 100000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
game-theory, dynamic-programming, math


## Company
hackwithinfy
