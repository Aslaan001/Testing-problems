## Title
Pulse Node Conditioner

## Slug
pulse-node-conditioner

## Difficulty
Easy

## Description
You are given a binary string where adjacent identical characters cancel each other out. This transformation happens repeatedly until no two neighboring symbols match.

Given the initial binary string s, simulate this chain reaction until no further cancellations occur and provide the resulting stable string. It can be shown the outcome is deterministic no matter the order in which removals might be imagined.

## Examples

### 1
#### Input
110

#### Output
0

#### Explanation
Remove "11" → "0".

### 2
#### Input
100011

#### Output
10

#### Explanation
Remove "00" → "1011"; then remove "11" → "10".

### 3
#### Input
10011

#### Output
1

#### Explanation
Removing "00" results in "111". Then, one pair of "11" is removed, leaving "1".
This example shows how a removal can create a new pair of adjacent identical characters.

## Input Format
- A single line containing the binary string s consisting only of characters '0' and '1'.

## Output Format
- Return a single line: the final string after repeatedly removing adjacent equal pairs until no more removals can be made.

## Constraints
- 1 ≤ |s| ≤ 10^5
- s consists only of characters '0' and '1'

## Time Limit
1 second

## Memory Limit
256 MB

## Tags 
strings, stack, greedy