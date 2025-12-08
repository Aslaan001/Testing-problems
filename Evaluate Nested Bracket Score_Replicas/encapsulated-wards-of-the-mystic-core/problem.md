## Title
Encapsulated Wards of the Mystic Core

## Slug
encapsulated-wards-of-the-mystic-core

## Difficulty
Medium

## Description

In this reimagined scenario, encapsulated wards of the mystic core represent a structured system where each nested enclosure contributes to an overall score. A base unit carries a value of 1, adjacent components add their values, and deeper nested layers amplify their contained value by a factor of two. Your task is to compute the final accumulated score of the given structured expression following these rules.

## Examples

### 1

#### Input
()

#### Output
1

### 2

#### Input
(())

#### Output
2

### 3

#### Input
()()

#### Output
2

## Input Format

A single balanced bracket string s.

## Output Format

Return one integer — the computed score of the string.

## Constraints

2 ≤ |s| ≤ 50  
Characters in s are '(' and ')'  
The string is guaranteed to be balanced  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
stack, parsing, recursion
