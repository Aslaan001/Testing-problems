## Title
Plaza With Monuments

## Slug
plaza-with-monuments

## Difficulty
Easy

## Description
You are standing in a plaza with monuments of varying elements. Two lists are given:

- The first list contains the plazas you are interested in.

- The second list shows the entire skyline of the city, which also includes the plazas from the first list.

For each plaza in the first list, you need to find the next taller plaza that appears to the right of it in the skyline. If no taller plaza exists, write -1 for that plaza.

Your job is to help determine the height of the next taller plaza for each plaza in the list of interest.

## Examples

## Examples

### 1
#### Input

nums1 = [4, 1, 2]
nums2 = [1, 3, 4, 2]

#### Output

[-1, 3, -1]

#### Explanation

For building of height 4, no taller building exists to the right → -1.

For height 1, the next taller building is 3.

For height 2, no taller building exists → -1.

### 2
#### Input

nums1 = [2, 4]
nums2 = [1, 2, 3, 4]

#### Output

[3, -1]

#### Explanation

For height 2, the next taller building is 3.

For height 4, there is no taller building, so the answer is -1.

## Input Format

First line: Integer n1, the size of nums1.

Second line: n1 space-separated integers, representing nums1.

Third line: Integer n2, the size of nums2.

Fourth line: n2 space-separated integers, representing nums2.

nums1 is always a subset of nums2.

## Output Format

Return an array of integers of length n1, where each element represents the next taller building for nums1[i].

If no taller building exists, output -1 for that position.

## Constraints

- 1 ≤ n1 ≤ n2 ≤ 10000

- 0 ≤ nums1[i], nums2[i] ≤ 10^4

- All integers in nums1 and nums2 are unique

## Time Limit

1 second

## Memory Limit

256 MB

## Tags

array, stack, monotonic-stack