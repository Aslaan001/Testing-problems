## Title

Release Channel Identifier Ordering

## Slug

release-channel-identifier-ordering

## Difficulty

Hard

## Description

A large distributed databases enforces strict ordering rules on sensitive identifiers used during
controlled releases. These identifiers are generated from a predefined character pool and must
always advance     in lexicographical order to preserve auditability and rollback safety.      Given
a pool of available characters and the currently active identifier, the release system requires
generation     of a new identifier that is strictly greater in lexicographical terms. To avoid
unnecessary version jumps, the     system mandates choosing the smallest possible identifier that
still satisfies the ordering constraint.      Your task is to compute this next valid identifier or
determine that no valid advancement is possible, ensuring     correctness in automated release
pipelines.

## Examples

### 1

#### Input

abc  
bba

#### Output

bca

#### Explanation

The permutations of "abc" in lexicographical order are:

"abc", "acb", "bac", "bca", "cab", "cba"

The lexicographically smallest permutation that is strictly greater than "bba" is "bca".

### 2

#### Input

leet  
code

#### Output

eelt

#### Explanation

Among all permutations of "leet", "eelt" is the smallest one that is lexicographically strictly greater than "code".

### 3

#### Input

leet  
codd

#### Output

eelt

## Input Format

- First line: string `s`
- Second line: string `target`

Both strings:
- Have equal length `n`
- Contain only lowercase English letters

## Output Format

- Return a single string — the lexicographically smallest permutation of `s` that is strictly greater than `target`
- If no such permutation exists, return an empty string

## Constraints

- 1 ≤ n ≤ 300  
- `s.length == target.length`  
- `s` and `target` consist only of lowercase English letters  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

greedy  
