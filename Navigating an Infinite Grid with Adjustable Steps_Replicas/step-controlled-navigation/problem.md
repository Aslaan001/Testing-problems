## Title
Step Controlled Navigation

## Slug
step-controlled-navigation

## Difficulty
Medium

## Description
In autonomous systems engineering, step controlled navigation is a fundamental problem when designing agents that operate in unbounded coordinate spaces.

An automated agent starts at a fixed origin point on a two-dimensional grid and maintains a configurable movement parameter that determines the distance covered in a single jump.
At each step, the agent may either move horizontally, move vertically, or adjust its movement capability by increasing the jump length.

The challenge is to plan an optimal sequence of actions that allows the agent to reach a specified target coordinate using the fewest possible moves.
Both movement and adjustment actions incur a cost of one move, and the grid itself imposes no boundaries.

The objective is to compute the minimum number of actions required to reach the destination while respecting the movement rules and ensuring efficiency at large coordinate values.


## Examples

### 1
#### Input
1 1  

#### Output
2  

#### Explanation
The robot can jump to (0, 1) and then to (1, 1).  
Increasing the leg length would cause the robot to overshoot the target.

### 2
#### Input
1 6  

#### Output
5  

#### Explanation
The robot first jumps to (1, 0), increases its leg length, and then makes successive jumps to reach the destination.

### 3
#### Input
8 4  

#### Output
6  

#### Explanation
The robot increases its leg length to 4, jumps to (0, 4), and then makes two jumps to reach (8, 4).

## Input Format
- Each test case consists of a single line containing two integers a and b — the coordinates of the target cell.

## Output Format
Return a single integer — the minimum number of moves required to reach the target cell.

## Constraints  
- 1 ≤ a, b ≤ 10^9  

## Time Limit
2 seconds

## Memory Limit
256 megabytes


## Tags
maths, hackwithinfy

## Company
infosys
