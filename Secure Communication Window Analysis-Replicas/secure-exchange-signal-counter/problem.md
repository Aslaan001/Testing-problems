## Title

Secure Exchange Signal Counter

## Slug

secure-exchange-signal-counter

## Difficulty

Medium

## Description

In security analytics pipelines, communication streams are examined to verify that critical
stages of an exchange occur together within bounded time intervals. Certain platforms require
the presence of multiple distinct markers before a transaction is considered complete. By
scanning contiguous portions of the signal stream, analysts can quantify how often all required
indicators co-occur, providing insight into protocol compliance and operational health.

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
