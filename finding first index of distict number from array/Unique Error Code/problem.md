## Title

Unique Error Code

## Slug

unique-error-code

## Difficulty

Medium

## Description

You are analyzing a system log containing error codes.  
Some errors occur multiple times, while others appear once.  

Find the `index of the first unique error code`.  

If all codes are repeated, return `-1`.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Error 5 occurs once → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Error 3 is unique → index 4.

## Input Format  

- First line: integer `n` — number of error codes.  
- Second line: `n` integers `arr[i]` — error codes.

## Output Format  

- A single integer — index of first unique error, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
