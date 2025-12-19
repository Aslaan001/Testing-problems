## Title
Village Path Enumeration

## Slug
village-path-enumeration

## Difficulty
Hard

## Description
In system modeling and workflow analysis, village path enumeration represents a constrained deterministic navigation problem.

A linear sequence of entities is indexed in increasing order, where each entity forwards control to exactly one other entity based on a predefined assignment.
Starting from any position, repeated transitions follow a fixed path determined entirely by these assignments.

The system must satisfy strict reachability guarantees.
Certain starting positions are required to eventually reach a designated control node, while others must be permanently excluded from reaching it.
Additionally, the control node itself must lie on a non-trivial cycle, ensuring that control can return to it after a positive number of transitions.

The objective is to count how many distinct assignment configurations satisfy all reachability and exclusion constraints.
Since the number of valid configurations can be very large, the result must be computed using modular arithmetic.


## Examples

### 1
#### Input
5 2  

#### Output
54  

#### Explanation
There are 54 different valid ways to assign plaque numbers so that the walking conditions are satisfied.

### 2
#### Input
7 4  

#### Output
1728  

#### Explanation
All assignments counted ensure that houses 1 through 4 can reach house 1, while houses 5 through 7 cannot.

## Input Format
- The input contains two space-separated integers n and k:
  - n — the total number of houses
  - k — the number of starting houses that must be able to reach house 1

## Output Format
Return a single integer — the number of valid plaque assignments modulo 10^9 + 7.

## Constraints
- 1 ≤ n ≤ 1000  
- 1 ≤ k ≤ min(8, n)  

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
maths, greedy, hackwithinfy

## Company
infosys
