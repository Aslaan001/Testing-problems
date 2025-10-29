## Title

First Peak Index in Mountain Trail

## Slug

first-peak-index-mountain-trail

## Difficulty

Medium

## Description

You are hiking in a mountain range represented as an array of elevations.  
Each integer represents the height of a point on your trail.

Find the first mountain peak index — the smallest index i where:  

- The sum of all previous elevations is less than the elevation at i.  
- The sum of all following elevations is also less than the elevation at i.

If no such mountain peak exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
At index 1:
Left sum = 1 < 5  
Right sum = 2 + 1 = 3 < 5  
→ Valid peak → output 1.

### 2

#### Input
5
1 3 2 4 1

#### Output
-1

#### Explanation
No index satisfies the condition.

## Input Format
- First line: integer n — number of points.  
- Second line: n integers — elevation values.

## Output Format
- One integer — the first valid peak index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
