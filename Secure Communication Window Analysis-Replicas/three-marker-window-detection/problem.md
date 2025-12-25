## Title

Three-Marker Window Detection

## Slug

three-marker-window-detection

## Difficulty

Medium

## Description

Within distributed environments, security-relevant markers are emitted sequentially as part     of
controlled interactions. To confirm that interactions are properly formed, the analysis
component searches for contiguous ranges where all mandatory markers appear at least once. This
window-based measurement supports auditing, diagnostics, and protocol verification.

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
