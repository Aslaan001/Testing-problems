## Title
Navigators Opening And Completing Warp Routes In A Galaxy Map

## Slug
navigators-opening-and-completing-warp-routes-in-a-galaxy-map

## Difficulty
Hard

## Description

You are managing navigators opening and completing warp routes in a galaxy map. Each mission consists of two actions: a start event and a completion event. For every mission i, the completion must occur after its corresponding start. Your task is to count how many valid sequences exist that include all start and completion events while respecting this rule. Return the result modulo 1000000007.

## Examples

### 1

#### Input
1

#### Output
1

#### Explanation
There is only one valid sequence: P1, D1.

### 2

#### Input
2

#### Output
6

#### Explanation
There are six valid sequences that respect the rule that each delivery must come after its pickup.

### 3

#### Input
3

#### Output
90

## Input Format

- The first line contains an integer n.

## Output Format

Return a single integer — the number of valid pickup-delivery sequences modulo 1000000007.

## Constraints

1 ≤ n ≤ 500

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
combinatorics, math, counting, dynamic-programming

## Company
hackwithinfy
