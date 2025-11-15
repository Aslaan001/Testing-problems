## Title
Product Display Stand Check

## Slug
product-display-stand-check

## Difficulty
Easy

## Decsription
In a scenario involving product display stand check, you are given an array `heights` representing the current arrangement. However, the correct arrangement should follow a non-decreasing sequence based on height. To determine how many items are out of place, compare the provided arrangement with its correctly sorted version. Count the number of indices where the two differ—this represents how many elements must be repositioned to achieve the required order.


## Examples

### 1

#### Input

heights = [1, 1, 4, 2, 1, 3]

#### Output

3

#### Explanation

Sorted order is `[1, 1, 1, 2, 3, 4]`. Mismatched indices are 2, 4, and 5.

### 2

#### Input

heights = [5, 1, 2, 3, 4]

#### Output

5

#### Explanation

All elements differ from their sorted positions.

### 3

#### Input

heights = [1, 2, 3, 4, 5]

#### Output

0

#### Explanation

Already sorted, so no mismatches.

## Input Format

- A single line containing an integer array `heights`.
- Array length ranges from 1 to 100.
- Each element is an integer in the range 1 to 100.

## Output Format

- Return a single integer representing the number of indices where `heights[i] != expected[i]`.

## Constraints

- 1 ≤ heights.length ≤ 100
- 1 ≤ heights[i] ≤ 100
- Sorting must preserve non-decreasing order
- No additional memory constraints beyond standard limits

## Time Limit

1 second

## Memory Limit

256 MB

## Tags

array, sorting, counting