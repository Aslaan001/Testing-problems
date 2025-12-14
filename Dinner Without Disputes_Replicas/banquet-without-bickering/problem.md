## Title
Banquet Without Bickering

## Slug
banquet-without-bickering

## Difficulty
Hard

## Description
In an event known as banquet without bickering, a host prepares several dishes laid out in a fixed order.
Each dish contains a certain number of servings, and a large pool of guests exists, each with personal preferences over which dishes they enjoy.

Exactly two guests will be invited.
Depending on whether none, one, or both of the invited guests like a dish, the servings are consumed accordingly.
If both guests like a dish with an odd number of servings, a disagreement occurs, which the host wants to avoid.

A pair of guests is acceptable only if no dish causes such a disagreement.
For every possible total number of servings the host consumes, determine how many valid guest pairs result in that exact amount.
Output the counts for all possible totals.

## Examples

### 1
#### Input
3 6  
A AB ABC AB BC C  
2 3 5  

#### Output
4 0 0 1 0 2 0 0 0 0 0

## Input Format
- First line: two integers n and m  
- Second line: m strings, where each string represents the set of dishes liked by a guest  
- Third line: n integers representing the number of portions in each dish  

Each string contains distinct uppercase letters and is sorted lexicographically.

## Output Format
Return ∑ai + 1 integers.  
The k-th integer (starting from k = 0) represents the number of valid guest pairs such that Monocarp eats exactly k portions.

## Constraints
1 ≤ n ≤ 20  
2 ≤ m ≤ 5⋅10⁵  
1 ≤ ai ≤ 2⋅10⁴  

## Time Limit
8 seconds

## Memory Limit
512 megabytes

## Tags
recursion, hackwithinfy

## Company
infosys
