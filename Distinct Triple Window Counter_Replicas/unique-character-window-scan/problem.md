## Title

Unique Character Window Scan

## Slug

unique-character-window-scan

## Difficulty

Easy

## Description

In real-time text processing and monitoring systems, it is often necessary to examine very small,
fixed-size segments of a data stream to ensure sufficient variability and avoid repetitive patterns.
Such checks are commonly applied in validation pipelines, signal quality analysis, and lightweight
anomaly detection. Given a continuous stream of lowercase characters, the system evaluates every
contiguous segment of a predefined length and verifies whether all characters within that segment
are unique. Each qualifying segment is counted independently, even if similar patterns appear
elsewhere in the stream. This task reflects practical applications of sliding window techniques and
localized pattern analysis in software systems.

## Examples

### 1

#### Input

xyzzaz

#### Output

1

#### Explanation

All substrings of length 3 are:

- xyz  
- yzz  
- zza  
- zaz  

Only xyz contains all distinct characters.

### 2

#### Input

aababcabc

#### Output

4

#### Explanation

All substrings of length 3 are:

- aab  
- aba  
- bab  
- abc  
- bca  
- cab  
- abc  

The good substrings are:

- abc  
- bca  
- cab  
- abc

## Input Format

- A single string s

## Output Format

- Return a single integer representing the number of good substrings of length three

## Constraints

- 1 ≤ length of s ≤ 100  
- s consists only of lowercase English letters

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

string

## Company

quora
