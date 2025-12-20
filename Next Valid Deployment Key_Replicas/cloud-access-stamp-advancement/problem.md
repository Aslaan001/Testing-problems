## Title

Cloud Access Stamp Advancement

## Slug

cloud-access-stamp-advancement

## Difficulty

Hard

## Description

Modern container orchestration layers manage access credentials that evolve incrementally to prevent
reuse and guarantee     monotonic progression. Credentials are constructed by permuting an approved
set of characters while respecting     strict lexicographical constraints.      Given the current
credential and the allowed character multiset, security policy dictates generating the
lexicographically smallest possible credential that is still strictly greater than the current one.
This task models the decision logic used in credential rotation engines and compliance verification
systems.

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
