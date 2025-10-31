## Title

Divisible Friendship Pairs

## Slug

divisible-friendship-pairs

## Difficulty

Medium

## Description

A group of friends decide to team up in pairs based on their compatibility score (given in an array).  
A friendship pair is valid only if the sum of their scores is divisible by a number `k`.

Check if all friends can be paired this way.  
Return `"YES"` if it’s possible, otherwise `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9,3)` and `(7,5)` make valid friendship pairs (sum divisible by 6).

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- Line 1: integer `n`.  
- Line 2: compatibility scores.  
- Line 3: integer `k`.

## Output Format

- `"YES"` if valid pairs exist, otherwise `"NO"`.

## Constraints

- 1 ≤ n ≤ 10⁵  
- 1 ≤ arr[i] ≤ 10⁹  
- 1 ≤ k ≤ 10⁹  
- `n` is even  

## Time Limit

1 second  

## Memory Limit

512 MB  

## Tags

arrays, sorting.
