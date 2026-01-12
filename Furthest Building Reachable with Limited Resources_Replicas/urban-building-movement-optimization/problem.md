## Title
Urban Building Movement Optimization

## Slug
urban-building-movement-optimization

## Difficulty  
Medium  

## Description

In a large-scale city skyline analysis tool, buildings are arranged in a straight sequence, each defined by a specific height value.

An operator begins at the first building and attempts to move forward through the sequence one structure at a time. Movement between adjacent buildings depends entirely on the difference in their heights and the availability of limited resources.

If the next building is of equal or lower height, progression requires no resources. When the next building is taller, the operator must compensate for the height increase using either construction materials or mechanical assistance. Construction materials must be consumed in an amount equal to the height difference, while mechanical assistance can bypass any height difference using a single unit.

Both resources are finite and may be consumed in any order. The challenge lies in allocating these resources efficiently to maximize forward progress without exhausting supplies prematurely.

The objective is to determine the furthest building index that can be reached by applying an optimal strategy for resource usage. Once no valid move can be made due to insufficient resources, traversal must stop, and the current position is considered the final reachable building.
## Examples  

### 1  

## Input  
7  
4 2 7 6 9 14 12  
5  
1  

## Output  
4  

## Explanation  

- Move from building 0 to 1 freely since 4 ≥ 2  
- Use 5 bricks to move from height 2 to 7  
- Move freely from 7 to 6  
- Use the ladder to move from 6 to 9  
- No resources remain to continue further  

### 2  

## Input  
9  
4 12 2 7 3 18 20 3 19  
10  
2  

## Output  
7  

### 3  

## Input  
4  
14 3 19 3  
17  
0  

## Output  
3  

## Input Format  

- The first line contains an integer n, the number of buildings  
- The second line contains n space-separated integers representing building heights  
- The third line contains an integer bricks  
- The fourth line contains an integer ladders  

## Output Format  

Return a single integer representing the index of the furthest building reachable.

## Constraints  

1 ≤ n ≤ 100000  
1 ≤ heights[i] ≤ 1000000  
0 ≤ bricks ≤ 1000000000  
0 ≤ ladders ≤ n  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

priority-queue  