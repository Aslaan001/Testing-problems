## Title
Restoring Order in the Cipher Sequence

## Slug
restoring-order-in-the-cipher-sequence

## Difficulty
Medium

## Description

In this thematic setting, restoring order in the cipher sequence must be restored to perfect balance. A sequence of symbols is given, and removing exactly one symbol may allow the remaining distinct characters to appear with uniform frequency. Your goal is to determine whether such a single removal can stabilize the pattern. If the resulting configuration achieves uniformity of all remaining characters, the answer is YES; otherwise, it is NO.

## Examples

### 1

#### Input
abcc

#### Output
YES

### 2

#### Input
aazz

#### Output
NO

## Input Format

A single string word.

## Output Format

Return `YES` or `NO` depending on whether removing one character can make all remaining letter frequencies equal.

## Constraints

2 ≤ |word| ≤ 100  
word contains only lowercase English letters

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
hashing, frequency-counting, simulation
