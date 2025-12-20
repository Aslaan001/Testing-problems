## Title

Retail Inventory Sync Log Rotation

## Slug

retail-inventory-sync-log-rotation

## Difficulty

Hard

## Description

A high-throughput digital platform processes sequential events and persists them as a compact string
representation to minimize storage overhead. To rebalance partitions and test fault recovery paths,
the platform periodically applies deterministic cyclic shifts that relocate the end portion of the
sequence to the beginning.  You are provided with the original event stream, a target stream
configuration, and an exact count of shift operations that must be performed during a maintenance
window. Each shift is parameterized by the size of the relocated suffix and is considered a distinct
operational decision.  Determine the total number of distinct operational plans that transform the
original stream into the target configuration using exactly the specified number of shifts. This
computation supports capacity planning, rollback simulations, and operational risk assessment.

## Examples

### 1

#### Input
abcd  
cdab  
2

#### Output
2

#### Explanation

There are two valid sequences of operations that transform `s` into `t` in exactly two steps.

### 2

#### Input
ababab  
ababab  
1

#### Output
2

#### Explanation

Two different suffix choices result in the same string, but are counted as separate operations.

## Input Format

- First line: string `s`
- Second line: string `t`
- Third line: integer `k`

## Output Format

- Return a single integer — the number of valid transformation sequences modulo `10^9 + 7`

## Constraints

- 2 ≤ n ≤ 5 × 10^5
- 1 ≤ k ≤ 10^15
- `s.length == t.length`
- `s` and `t` consist only of lowercase English letters

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

dynamic-programming  
