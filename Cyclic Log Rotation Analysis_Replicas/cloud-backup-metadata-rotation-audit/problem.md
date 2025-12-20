## Title

Cloud Backup Metadata Rotation Audit

## Slug

cloud-backup-metadata-rotation-audit

## Difficulty

Hard

## Description

Large-scale operational systems often validate their data movement logic by replaying logs under
controlled permutations. One such permutation involves cyclically rotating the log by extracting a
suffix and prepending it to the sequence.  You are tasked with assessing a validation run where an
initial log must reach a predefined target state using exactly a fixed number of these rotations.
Although multiple rotations may lead to the same intermediate log, each rotation choice is treated
as a separate decision for validation metrics.  Compute the number of distinct decision sequences
that successfully complete the validation run. This metric feeds into reliability scoring and
automated verification pipelines.

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
