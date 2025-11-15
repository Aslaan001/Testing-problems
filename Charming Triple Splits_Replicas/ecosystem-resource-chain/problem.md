## Title  
Ecosystem Resource Chain  

## Slug  
ecosystem-resource-chain  

## Difficulty  
Medium  

## Description  

In the world of Ecosystem Resource Chain, you are given a sequence representing a structured progression of events.

Your task is to examine this sequence and determine how many meaningful ways it can be split into three continuous, non-empty segments. These segments represent successive phases within the ecosystem resource chain process, preserving their exact order.

A split is considered valid if the first phase mirrors the beginning of the second, or if the second phase mirrors the beginning of the third. These prefix-based relationships indicate consistency or repetition within the underlying system being analyzed.

Count all distinct positions where the sequence can be divided into these three parts such that at least one of the prefix conditions holds true.

## Examples  

### 1  

#### Input  
4  
1 1 2 1  

#### Output  
2  

#### Explanation  
The valid charming splits are:  
nums1 = [1], nums2 = [1, 2], nums3 = [1]  
nums1 = [1], nums2 = [1], nums3 = [2, 1]  

### 2  

#### Input  
4  
1 2 3 4  

#### Output  
0  

#### Explanation  
There are no valid splits since no prefix relationship exists between parts.  

### 3  

#### Input  
5  
2 2 2 2 2  

#### Output  
6  

#### Explanation  
Every possible partition forms valid prefixes because all values are identical.  

## Input Format  

First line contains an integer n — the number of elements in the array.  
Second line contains n space-separated integers representing nums.  

## Output Format  

Return a single integer — the total number of charming splits that can be made.  

## Constraints  

1 ≤ n ≤ 5000  
0 ≤ nums[i] ≤ 50  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
arrays.
