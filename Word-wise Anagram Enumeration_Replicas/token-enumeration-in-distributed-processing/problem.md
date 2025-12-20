## Title

Token Enumeration in Distributed Processing

## Slug

token-enumeration-in-distributed-processing

## Difficulty

Hard

## Description

A high-volume legal document analyzer manages textual records composed of multiple space-delimited words.
For indexing, analytics, and compliance verification, the platform must quantify how many
distinct textual variants can be generated while preserving the structural integrity of
the original content.

Each record is treated as an ordered sequence of words. While the order and boundaries of
words are immutable, the characters inside each word may be rearranged independently to
produce alternative representations that are semantically equivalent for downstream
processing tasks.

Two textual records are considered equivalent variants only if they contain the same number
of words, each corresponding word consists of exactly the same multiset of characters, and
no characters cross word boundaries during rearrangement.

The system must compute the total number of distinct valid variants that can be formed under
these constraints. Because the number of possibilities grows rapidly with word length, the
result must be reported using modular arithmetic consistent with production-grade systems.

This calculation is fundamental for capacity planning, index sizing, and correctness testing
in large-scale text processing pipelines.

## Examples

### 1

#### Input
too hot

#### Output
18

#### Explanation

The word `"too"` has 3 characters with one repeated character, resulting in 3 distinct permutations.
The word `"hot"` has 3 unique characters, resulting in 6 distinct permutations.

Total anagrams = 3 × 6 = 18

### 2

#### Input
aa

#### Output
1

#### Explanation

The word `"aa"` has only one distinct permutation.

## Input Format

- A single line containing the string `s`

## Output Format

- Return a single integer representing the number of distinct valid anagrams of `s`, modulo `1000000007`

## Constraints

- 1 ≤ length of `s` ≤ 100000
- `s` consists only of lowercase English letters and spaces
- There is exactly one space between consecutive words

## Time Limit

1 second

## Memory Limit

512 MB

## Tags
math
