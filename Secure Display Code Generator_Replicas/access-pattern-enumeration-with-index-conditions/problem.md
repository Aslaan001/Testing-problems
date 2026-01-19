## Title
Access Pattern Enumeration with Index Conditions
Secure Display Code Generator

## Slug
access-pattern-enumeration-with-index-conditions
secure-display-code-generator

## Difficulty

Medium

## Description

In a restricted input validation system, numeric codes are generated to regulate visibility or access based on strict formatting rules.

Each code is represented as a sequence of digits with a predefined length. The validity of a code depends entirely on the position of each digit and the allowed digit set associated with that position.

Digits placed at even indexed positions must belong to a fixed set of even valued digits. Digits placed at odd indexed positions must belong to a fixed set of prime valued digits. Leading zeros are permitted and do not affect validity.

Given a required code length, the objective is to determine the total number of distinct valid codes that can be formed while respecting all positional digit constraints.

Since the number of valid combinations grows rapidly with increasing length, the result must be computed using modular arithmetic to ensure numerical stability within system limits.
## Examples

### 1

#### Input

n = 1

#### Output

5

#### Explanation

Only one position exists, which is an even index.
The allowed digits are: 0, 2, 4, 6, 8

Total valid codes = 5

### 2

#### Input

n = 4

#### Output

400

#### Explanation

Positions:
- Index 0 and 2 allow 5 possible digits each
- Index 1 and 3 allow 4 possible digits each

Total valid codes = 5 × 4 × 5 × 4 = 400

### 3

#### Input

n = 50

#### Output

564908303

#### Explanation

The number of valid codes grows exponentially.
The final result is computed using modular arithmetic.

## Input Format

- A single integer n representing the length of the code

## Output Format

- Return a single integer representing the number of valid codes modulo 10^9 + 7

## Constraints

1 <= n <= 10^15

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

maths, recursion.  