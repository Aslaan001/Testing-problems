## Title

Operational Arithmetic String Processor

## Slug

operational-arithmetic-string-processor

## Difficulty

Hard

## Description

In enterprise-grade financial and analytical platforms, arithmetic expressions are frequently
transmitted as raw text rather than structured code. These expressions may include nested groupings,
signed values, and irregular spacing, yet must be evaluated deterministically and securely. The
computation layer is required to interpret each symbol manually, respecting operator rules and
parenthetical boundaries, without delegating execution to language-level evaluators. Given a valid
expression string, the system must parse tokens, resolve nested subexpressions, and compute the
final integer result accurately. This problem reflects real-world requirements in secure financial
calculation engines, rule-based processing systems, and controlled execution environments where
explicit parsing is mandatory.

## Examples

### 1

#### Input

1 + 1

#### Output

2

#### Explanation

The expression evaluates directly to 2.

### 2

#### Input

2-1 + 2

#### Output

3

#### Explanation

Step-by-step evaluation results in 3.

### 3

#### Input

(1+(4+5+2)-3)+(6+8)

#### Output

23

#### Explanation

Nested parentheses are resolved first, then combined to produce the final value.

## Input Format

- A single string `s` representing a valid arithmetic expression

## Output Format

- Return a single integer representing the evaluated result of the expression

## Constraints

- 1 ≤ length of `s` ≤ 300000  
- `s` consists only of digits, spaces, `+`, `-`, `(`, and `)`  
- No two operators appear consecutively  
- Unary `-` is allowed, unary `+` is not allowed  
- Expression is always valid  
- Result fits in 32-bit signed integer range

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

string

## Company

snapchat
