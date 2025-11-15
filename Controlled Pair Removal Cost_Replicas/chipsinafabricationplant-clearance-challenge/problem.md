## Title
ChipsInAFabricationPlant Clearance Challenge

## Slug
chipsinafabricationplant-clearance-challenge

## Difficulty
Medium

## Description

You are handling a collection of chips in a fabrication plant, each represented by an integer in an array.

Your objective is to clear the entire collection while keeping the overall removal cost as low as possible.  
The removal obeys the following process:

1. Whenever at least three items remain:  
   You must pick any two from the first three entries and eliminate them.  
   The cost for this action is determined by the higher value among those two selected items.

2. When fewer than three items are left:  
   You must clear all remaining items together in a single action.  
   The cost of this final action is simply the maximum value of the remaining items.

Your task is to compute the minimum total cost needed to fully remove the entire collection.

## Examples  

### 1  

#### Input  
4  
6 2 8 4

#### Output  
12

#### Explanation  
Remove 6 and 8 from the first three elements → cost = 8  
Remaining array: 2 4  
Remove remaining elements → cost = 4  
Total cost = 8 + 4 = 12

### 2  

#### Input  
4  
2 1 3 3

#### Output  
5

#### Explanation  
Remove 2 and 1 → cost = 2  
Remaining array: 3 3  
Remove remaining elements → cost = 3  
Total cost = 2 + 3 = 5

## Input Format  

- The first line contains an integer n, the number of elements in the array.  
- The second line contains n integers representing the array nums.

## Output Format  

Return a single integer representing the minimum total cost needed to remove all elements.

## Constraints  

1 ≤ n ≤ 1000  
1 ≤ nums[i] ≤ 10^6  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

greedy.