## Title
Planetary Orbit Average

## Slug
planetary-orbit-average

## Difficulty
Easy

## Description

Astronomers record gravitational intensities along a planet’s orbit.  
Find the `k` consecutive intensities with the highest average.

Return this maximum average intensity, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Segment `[12, -5, -6, 50]` gives (12 - 5 - 6 + 50)/4 = 12.75.

### 2
#### Input
1
5
1

#### Output
5.00000

#### Explanation
Only one orbit point — average = 5.00000.

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the maximum average gravitational value.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ gravity[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
