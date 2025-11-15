## Title  
End-Flip Operations Minimizer

## Slug  
end-flip-operations-minimizer

## Difficulty  
Medium  

## Description  

You are given a binary array `nums` representing status lights on a machine console. Each value is either `0` or `1`.

You may perform the following operation any number of times:

Choose an index `i` and flip all elements from index `i` to the end of the array. Flipping converts `0 → 1` and `1 → 0`.

Your goal is to determine the minimum number of such operations required to ensure that every element in the array becomes `1`.

## Examples  

### 1  

#### Input  
5  
0 1 1 0 1  

#### Output  
4  

#### Explanation  
Operations example:  
i = 1 → nums becomes [0,0,0,1,0]  
i = 0 → nums becomes [1,1,1,0,1]  
i = 4 → nums becomes [1,1,1,0,0]  
i = 3 → nums becomes [1,1,1,1,1]

### 2  

#### Input  
4  
1 0 0 0  

#### Output  
1  

#### Explanation  
Choosing index `1` flips all remaining elements → [1,1,1,1].

## Input Format  

- The first line contains an integer `n` — the size of the array.  
- The second line contains `n` space-separated binary integers.

## Output Format  

Return a single integer — the minimum number of operations needed to make all elements equal to `1`.

## Constraints  

1 ≤ n ≤ 100000  
0 ≤ nums[i] ≤ 1  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

greedy.  
