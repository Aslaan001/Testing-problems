## Title

Fraud Detection Signal Rotation Study

## Slug

fraud-detection-signal-rotation-study

## Difficulty

Hard

## Description

A regulated enterprise system records critical operational data as a serialized character stream to
satisfy compliance, traceability, and historical reconstruction requirements. During scheduled
audits, the organization enforces controlled cyclic realignments of this stream to validate
redundancy mechanisms and replay correctness across replicas. Each adjustment moves a trailing
segment to the front, altering alignment while preserving internal order.  Given a recorded baseline
stream and an expected post-audit stream, both of identical length, the audit framework mandates
that exactly a fixed number of such realignment actions be executed. Individual actions are uniquely
identified by the chosen segment length, regardless of whether the intermediate result matches a
prior state.  Your task is to compute how many distinct audit-compliant action sequences achieve the
required final configuration using precisely the mandated number of steps. This analysis is
essential for verifying policy enforcement and automated compliance tooling.

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
