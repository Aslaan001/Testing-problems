## Title

Supply Chain Visibility Log Cycling

## Slug

supply-chain-visibility-log-cycling

## Difficulty

Hard

## Description

An enterprise-grade processing system stores ordered records in a string-based buffer for efficient
replication. During stress testing, the system enforces a precise number of cyclic buffer rotations,
each moving a selectable suffix to the front, to evaluate stability under repeated transformations.
Given the initial buffer state, the expected final state, and the exact number of rotations
required, your task is to enumerate all distinct rotation sequences that satisfy the test
conditions. Each rotation is uniquely identified by its chosen suffix length.  The resulting count
is critical for validating test coverage and ensuring deterministic behavior under repeated
structural modifications.

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
