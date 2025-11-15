## Title  
Secure Lock Code Sets

## Slug  
secure-lock-code-sets

## Difficulty  
Medium

## Description  

Lock codes differing by k can be brute-forced together. Count secure code subsets.

## Examples  

### Example 1

Input  
3  
2 4 6  
2

Output  
4

Explanation  
Valid harmonious selections include:
[2], [4], [6], and [2, 6].

### Example 2

Input  
1  
1  
1

Output  
1

Explanation  
Only one selection is possible.

## Input Format  

- The first line contains an integer n.  
- The second line contains n space-separated integers.  
- The third line contains an integer k.

## Output Format  

Return the total number of non-empty harmonious selections.

## Constraints  

1 ≤ n ≤ 18  
1 ≤ values[i] ≤ 1000  
1 ≤ k ≤ 1000  

## Time Limit  

1 second  

512 MB

## Tags  

combinatorial counting.
