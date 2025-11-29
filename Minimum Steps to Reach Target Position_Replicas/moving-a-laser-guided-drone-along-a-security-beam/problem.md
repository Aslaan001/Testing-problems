## Title
Moving A Laser-Guided Drone Along A Security Beam

## Slug
moving-a-laser-guided-drone-along-a-security-beam

## Difficulty
Hard

## Description
You are navigating a vehicle representing moving a laser-guided drone along a security beam on an infinite line. It starts at 0 with speed +1 and can accelerate or reverse direction. Your goal is to reach the exact target position using the minimum number of commands.



### 1

#### Input
3

#### Output
2

#### Explanation
A minimal sequence is "A A".  
The car moves: 0 → 1 → 3.

### 2

#### Input
6

#### Output
5

#### Explanation
A valid shortest sequence is "A A A R A".  
The car moves: 0 → 1 → 3 → 7 → 7 → 6.

## Input Format

- A single integer target.

## Output Format

Return a single integer — the minimum number of instructions needed to reach the target.

## Constraints

1 ≤ target ≤ 10000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
breadth-first-search, dynamic-programming, shortest-path

## Company
hackwithinfy
