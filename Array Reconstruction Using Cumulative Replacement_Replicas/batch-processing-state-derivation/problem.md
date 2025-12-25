## Title

Batch Processing State Derivation

## Slug

batch-processing-state-derivation

## Difficulty

Hard

## Description

In a large-scale enterprise system, an internal engine manages a vector of numerical state
indicators representing cumulative operational values. At system initialization, all indicators
start from a uniform baseline. The platform permits controlled overrides where any single position
may be replaced with the total sum of the current vector, reflecting scenarios such as metric
rollups, ledger consolidation, or snapshot promotion. Given a final observed configuration,
engineers must determine whether such a configuration could have been produced through a sequence of
valid override operations. The verification process must strictly adhere to the defined operational
rules and scale efficiently for large vectors. This problem captures real-world concerns in system
recovery, audit replay, and deterministic state reconstruction where cumulative transformations
define reachability.

## Examples

### 1

#### Input

3  
9 3 5

#### Output

YES

#### Explanation

Start with arr = [1, 1, 1]

- Sum = 3, replace index 1 → [1, 3, 1]  
- Sum = 5, replace index 2 → [1, 3, 5]  
- Sum = 9, replace index 0 → [9, 3, 5]  

The target array is successfully constructed.

### 2

#### Input

4  
1 1 1 2

#### Output

NO

#### Explanation

There is no sequence of valid operations that can transform [1, 1, 1, 1] into the target array.

### 3

#### Input

2  
8 5

#### Output

YES

#### Explanation

The target array can be constructed by repeatedly replacing one element with the current sum.

## Input Format

- First line contains an integer n, the length of the target array.
- Second line contains n space-separated integers representing the target array.

## Output Format

- Return true if the target array can be constructed, otherwise return false.

## Constraints

- 1 ≤ n ≤ 50000  
- 1 ≤ target[i] ≤ 10^9

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company


