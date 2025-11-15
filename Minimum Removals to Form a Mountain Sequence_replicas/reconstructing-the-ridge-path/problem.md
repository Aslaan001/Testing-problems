## Title  
Reconstructing the Ridge Path

## Slug  
reconstructing-the-ridge-path

## Difficulty  
Hard  

## Description  

You are given an integer array vals of length n.

In this storyline variant, the array represents a terrain profile you must reshape into a valid mountain form by removing as few points as possible. A valid mountain must strictly rise to a single peak and then strictly fall.

Your goal is to determine the minimum number of elements that must be removed so that the sequence becomes a proper mountain.
## Examples  

### 1  

#### Input  
3  
1 3 1  

#### Output  
0  

#### Explanation  
The sequence [1, 3, 1] already forms a valid mountain with peak 3.  


### 2  

#### Input  
8  
2 1 1 5 6 2 3 1  

#### Output  
3  

#### Explanation  
Removing indices 0, 1, and 5 gives [1, 5, 6, 3, 1], which is a valid mountain.  


### 3  

#### Input  
7  
1 2 3 4 3 2 1  

#### Output  
0  

#### Explanation  
The sequence is already a valid mountain with peak 4.  


## Input Format  

The first line contains an integer n — the number of elements in the sequence.  
The second line contains n space-separated integers representing the array vals.  


## Output Format  

Return a single integer — the minimum number of elements that must be removed to make the sequence a valid mountain.  


## Constraints  

3 ≤ n ≤ 1000  
1 ≤ vals[i] ≤ 10⁹  


## Time Limit  
1 second  

## Memory Limit  
256 MB  


## Tags  
arrays, dynamic-programming, longest-increasing-subsequence, optimization  