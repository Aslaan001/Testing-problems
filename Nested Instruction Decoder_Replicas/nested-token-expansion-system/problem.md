## Title

Nested Token Expansion System

## Slug

nested-token-expansion-system

## Difficulty

Medium

## Description

A distributed backend exchanges operational operations in a compact symbolic format to     minimize
network overhead. Instead of transmitting repeated instruction blocks, the service     encodes
repetition counts alongside bracketed segments. These segments may themselves reference
additional encoded blocks, forming a layered structure. The decoding component must process the
encoded stream sequentially, expanding inner structures before applying outer repetitions, and
finally producing a fully materialized instruction stream suitable for execution.

## Examples

### 1

#### Input

3[a]2[bc]

#### Output

aaabcbc

#### Explanation

- `3[a]` expands to `aaa`
- `2[bc]` expands to `bcbc`
- Final result is `aaabcbc`

### 2

#### Input

3[a2[c]]

#### Output

accaccacc

#### Explanation

- Inner segment `2[c]` becomes `cc`
- Outer segment `3[a2[c]]` becomes `accaccacc`

### 3

#### Input

2[abc]3[cd]ef

#### Output

abcabccdcdcdef

#### Explanation

- `2[abc]` expands to `abcabc`
- `3[cd]` expands to `cdcdcd`
- Remaining `ef` is appended as-is

## Input Format

- A single string `s` representing the encoded instruction sequence

## Output Format

- Return a single string representing the fully decoded instruction sequence

## Constraints

- 1 ≤ length of `s` ≤ 30
- `s` consists only of lowercase English letters, digits, and square brackets
- All repeat counts are in the range 1 to 300
- The decoded output length will not exceed 100000

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

string

## Company

snapchat
