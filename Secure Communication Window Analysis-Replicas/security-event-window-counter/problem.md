## Title

Security Event Window Counter

## Slug

security-event-window-counter

## Difficulty

Medium

## Description

Operational security reviews often rely on pattern density rather than isolated events.     By
examining adjacent slices of a signal timeline, reviewers can determine how frequently     complete
exchanges occur. Each slice is considered valid only if it demonstrates the presence     of all
expected signal categories, ensuring full coverage within the observed window.

## Examples

### 1

#### Input

abcabc

#### Output

10

#### Explanation

The valid communication windows are:

- abc  
- abca  
- abcab  
- abcabc  
- bca  
- bcab  
- bcabc  
- cab  
- cabc  
- abc  

Each of these substrings contains all three required signal markers.

### 2

#### Input

aaacb

#### Output

3

#### Explanation

The valid communication windows are:

- aaacb  
- aacb  
- acb  

### 3

#### Input

abc

#### Output

1

#### Explanation

Only one contiguous window exists, and it contains all required signals.

## Input Format

- A single string `s` representing the communication signal stream  
- The string consists only of characters `a`, `b`, and `c`

## Output Format

- Return a single integer — the number of valid communication windows

## Constraints

- 3 ≤ length of `s` ≤ 5 × 10⁴  
- `s[i]` ∈ { `a`, `b`, `c` }

## Time Limit

1 second

## Memory Limit

512 MB

## Company

deshaw

## Tags

string
