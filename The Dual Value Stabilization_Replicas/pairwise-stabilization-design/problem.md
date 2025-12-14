## Title
Pairwise Stabilization Design

## Slug
pairwise-stabilization-design

## Difficulty
Hard

## Description
In a process known as pairwise stabilization design, a system maintains a row of containers indexed from 1 to n.
Initially, each container holds a distinct value corresponding to its index.

The system provides access to a hidden but consistent function that combines two values into a new one.
Although the exact behavior of this function is unknown, it always produces the same output for the same input pair.

You may repeatedly choose pairs of container indices and replace both values with the result of applying the function to them.
The challenge is to design a sequence of such pairwise operations so that, regardless of how the function behaves,
the final configuration of the system contains no more than two distinct values.

Output any sequence of operations that guarantees this outcome.

## Examples

### 1
#### Input
3

#### Output
2
1 2
2 3

### 2
#### Input
4

#### Output
8
1 2
3 4
1 3
2 4
1 2
3 4
1 3
2 4

## Input Format
- A single integer n representing the size of the array.

## Output Format
- First line contains an integer q, the number of operations.
- Each of the next q lines contains two integers x and y describing one operation.

## Constraints
- 1 ≤ n ≤ 15000
- 0 ≤ q ≤ 500000
- 1 ≤ x, y ≤ n

## Time Limit
3 seconds

## Memory Limit
256 megabytes


## Tags
recursion, hackwithinfy

## Company
infosys
