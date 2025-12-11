## Title
Astral Glyph Compression

## Slug
astral-glyph-compression

## Difficulty
Easy

## Description
In a world driven by astral glyph compression, sequences often destabilize when identical units collide. Each time two adjacent symbols share the same form, they annihilate instantly, releasing energy back into the system. This chain reaction continues until the sequence reaches a perfectly stable state where no further identical adjacencies remain. You are given an initial binary sequence that behaves according to this rule. Your task is to simulate its evolution, observing how repeated cancellations reshape the pattern before it finally settles. The final stabilized sequence is always deterministic and independent of the order in which the cancellations occur. Determine this final form.

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
- Print a single line: the final string after repeatedly removing adjacent equal pairs until no more removals can be made.

## Constraints
- 1 ≤ |s| ≤ 10^5
- s consists only of characters '0' and '1'

## Time Limit
1 second

## Memory Limit
256 MB

## Tags 
string, stack, greedy
