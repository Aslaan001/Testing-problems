## Title

Encoded Pattern Reconstruction

## Slug

encoded-pattern-reconstruction

## Difficulty

Medium

## Description

To reduce storage and bandwidth usage, an execution planner stores instruction streams using
numeric repetition markers combined with bracket-delimited instruction groups. These groups can
be nested arbitrarily, requiring the processor to respect strict expansion ordering. The decoding
logic must reconstruct the exact instruction stream by resolving each level of nesting while
ensuring correctness and output size limits.

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
