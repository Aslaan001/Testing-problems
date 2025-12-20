## Title

Update Certificate Key Progression

## Slug

update-certificate-key-progression

## Difficulty

Hard

## Description

In identity management services, version identifiers must progress deterministically to maintain
traceability across environments. Identifiers are assembled by rearranging approved symbols without
introducing     external characters.      From a given identifier pool and an active identifier,
determine the smallest lexicographical permutation that     represents a valid forward step. If no
such step exists, the system must explicitly signal exhaustion.      This mechanism ensures minimal
advancement while preserving strict ordering guarantees.

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
