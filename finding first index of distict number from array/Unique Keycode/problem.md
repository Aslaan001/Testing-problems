## Title

Unique Keycode

## Slug

unique-keycode

## Difficulty

Medium

## Description

A security system logs keycodes entered during the day.  
Some keycodes repeat due to retries.  

Find the `index of the first keycode` that appears only once.  

Return `-1` if all are duplicates.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Keycode 5 unique → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Keycode 3 appears once → index 4.

## Input Format  

- First line: integer `n` — number of keycodes.  
- Second line: `n` integers `arr[i]` — entered keycodes.

## Output Format  

- A single integer — index of first unique keycode, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
