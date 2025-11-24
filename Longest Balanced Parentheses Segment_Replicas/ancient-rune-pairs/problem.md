## Title
Ancient Rune Pairs

## Slug
ancient-rune-pairs

## Difficulty

Hard

## Description
You are given a string made up of two characters representing parts of ancient rune pairs.  
Your task is to determine the length of the longest substring that forms a valid, balanced ancient rune pairs sequence.

A substring is considered balanced if:

- every opening symbol has a matching closing symbol, and  
- the structure is properly nested.

Return the maximum length of any such substring.

## Examples

### 1

#### Input
(() 

#### Output
2

#### Explanation
The substring "()" is the longest balanced segment.

### 2

#### Input
)()()) 

#### Output
4

#### Explanation
The longest balanced segment is "()()".

### 3

#### Input
()

#### Output
2

## Input Format

- A single string s consisting only of '(' and ')'.

## Output Format

- Return a single integer representing the length of the longest balanced parentheses substring.

## Constraints

- 0 ≤ |s| ≤ 10^5  
- s contains only '(' and ')'

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

stack, dynamic-programming, two-pointers, strings
