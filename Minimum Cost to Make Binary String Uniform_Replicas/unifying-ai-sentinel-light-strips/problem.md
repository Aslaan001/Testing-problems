## Title
Unifying Ai Sentinel Light Strips

## Slug
unifying-ai-sentinel-light-strips

## Difficulty
Hard

## Description
You are working with a binary sequence representing unifying AI sentinel light strips. You may flip any prefix or suffix at specified costs, where flipping inverts all bits involved. Your goal is to compute the minimum total cost required to make the entire sequence uniform (all 0s or all 1s).



### 1

#### Input
0011

#### Output
2

#### Explanation
A suffix flip at index 2 converts the string to 0000 with a cost of 2.  
This is the minimum possible cost.

### 2

#### Input
010101

#### Output
9

#### Explanation
One optimal sequence is:

i = 2 → prefix flip → cost 3 → 101101  
i = 1 → prefix flip → cost 2 → 011101  
i = 0 → prefix flip → cost 1 → 111101  
i = 4 → suffix flip → cost 2 → 111110  
i = 5 → suffix flip → cost 1 → 111111  

Total cost = 9.

## Input Format

- A single binary string s.

## Output Format

Return a single integer representing the minimum cost to make all characters equal.

## Constraints

1 ≤ n ≤ 100000  
s[i] ∈ {0, 1}

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
greedy, dynamic-programming, string, prefix-processing

## Company
hackwithinfy
