## Title

Binary Logic Accumulation

## Slug

binary-logic-accumulation

## Difficulty

Easy

## Description

In modern communication and computing systems, numerical information is frequently represented and
exchanged in binary form to align with hardware and protocol constraints. At this level, arithmetic
operations must be performed directly on binary-encoded values without relying on higher-level
numeric abstractions. Given two independent binary signals, the system must accurately compute their
combined value while preserving strict formatting rules such as the absence of leading zeros. This
task reflects real-world requirements in digital logic design, protocol validation, embedded
software, and low-level data processing where correctness and efficiency of binary arithmetic are
essential.

## Examples

### 1

#### Input

11  
1

#### Output

100

#### Explanation

Binary addition:

- 11 (3 in decimal)  
- 1 (1 in decimal)  

Sum = 4 → binary representation is 100.

### 2

#### Input

1010  
1011

#### Output

10101

#### Explanation

Binary addition:

- 1010 (10 in decimal)  
- 1011 (11 in decimal)  

Sum = 21 → binary representation is 10101.

## Input Format

- First line contains a binary string `a`.
- Second line contains a binary string `b`.

## Output Format

- Return a single binary string representing the sum of `a` and `b`.

## Constraints

- 1 ≤ length of `a`, `b` ≤ 10000  
- `a` and `b` consist only of characters `0` and `1`  
- No leading zeros except for the string `"0"`

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

string

## Company

snapchat
