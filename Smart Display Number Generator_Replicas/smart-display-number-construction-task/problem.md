## Title
Smart Display Number Construction Task
Smart Display Number Generator

## Slug
smart-display-number-construction-task
smart-display-number-generator

## Difficulty

Easy

## Description

In a smart led display manufacturing system, numeric values are assembled using a limited inventory of digit components.

Each output must consist of exactly three digits arranged side by side to form a valid display value. The generated value must be even, must not begin with zero, and must respect the available count of each digit component.

Digits can only be reused according to their frequency in the provided inventory, and duplicate display values must not be produced more than once. Only combinations that satisfy all constraints are considered valid.

The task is to generate every valid three digit even value that can be formed from the given digit set and return the complete collection in sorted order. If no valid value can be produced, the result must be an empty list.
## Examples

### 1

#### Input

digits = [2, 1, 3, 0]

#### Output

[102, 120, 130, 132, 210, 230, 302, 310, 312, 320]

#### Explanation

The display system forms all possible three-digit even numbers using the available digits.
Numbers starting with zero or ending with an odd digit are rejected.

### 2

#### Input

digits = [2, 2, 8, 8, 2]

#### Output

[222, 228, 282, 288, 822, 828, 882]

#### Explanation

Digits can only be reused according to their availability.
The digit 8 appears twice, so it can be used twice in numbers such as 288, 828, and 882.

### 3

#### Input

digits = [3, 7, 5]

#### Output

[]

#### Explanation

No even digit is available, so the display system cannot generate any valid number.

## Input Format

- A single array of integers named digits
- Each integer represents a digit between 0 and 9

## Output Format

- Return a sorted array of unique valid display numbers

## Constraints

3 <= digits.length <= 100  
0 <= digits[i] <= 9  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

recursion