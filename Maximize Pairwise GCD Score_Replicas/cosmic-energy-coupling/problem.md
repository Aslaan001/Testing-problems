## Title

Cosmic Energy Coupling

## Slug

cosmic-energy-coupling

## Difficulty

Hard

## Description

In the process known as cosmic energy coupling, a collection of numbered artifacts is prepared for a sequence of operations.
The collection contains exactly 2 * n artifacts, and all of them must be used.

During each operation, two unused artifacts are selected and permanently bound together.
The effectiveness of this binding depends on a compatibility value derived from the two artifacts.
This value is multiplied by the operation index to produce a score contribution.

After binding, the selected artifacts are removed from future consideration.
Your objective is to determine the order of bindings that yields the maximum possible total score after all operations are completed.

## Examples

### 1

#### Input
1
1 2

#### Output
1

#### Explanation

Only one pair exists.  
Score = 1 * gcd(1, 2) = 1.

### 2

#### Input
2
3 4 6 8

#### Output
11

#### Explanation

One optimal pairing is:  
(1 * gcd(3, 6)) + (2 * gcd(4, 8)) = 3 + 8 = 11.

### 3

#### Input
3
1 2 3 4 5 6

#### Output
14

#### Explanation

An optimal selection is:  
(1 * gcd(1, 5))  
+ (2 * gcd(2, 4))  
+ (3 * gcd(3, 6))  
= 14.

## Input Format

- Array nums of size 2 * n
- All integers are positive

## Output Format

- Return the maximum total score after performing n operations

## Constraints

- 1 ≤ n ≤ 7  
- nums.length = 2 * n  
- 1 ≤ nums[i] ≤ 10^6  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

BitmaskDP,Combinatorics
