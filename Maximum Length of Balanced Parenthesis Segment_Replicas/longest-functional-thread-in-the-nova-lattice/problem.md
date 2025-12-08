## Title
Longest Functional Thread in the Nova Lattice

## Slug
longest-functional-thread-in-the-nova-lattice

## Difficulty
Hard

## Description

In this reimagined scenario, longest functional thread in the nova lattice represents a sequence whose internal structure must remain perfectly stable. A segment is considered valid only if its internal ordering forms a fully balanced pattern, with every initiating mark properly closed. Your task is to determine the longest contiguous portion of the sequence that preserves this structural correctness. If no such stable interval exists, the correct result is 0.

## Examples

### 1

#### Input
(()

#### Output
2

### 2

#### Input
)()())

#### Output
4

### 3

#### Input
)

#### Output
0

## Input Format

A single string s.

## Output Format

Return one integer — the maximum length of any balanced parenthesis segment.

## Constraints

0 ≤ |s| ≤ 30000  
Characters in s are '(' or ')'

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
stack, dynamic-programming, two-pointers
