## Title

Orbital Crew Synchronization

## Slug

orbital-crew-synchronization

## Difficulty

Hard

## Description

A space agency is preparing a deep-space expedition involving astronauts with different mission codes.
All astronauts must be assigned into exactly k spacecraft modules, each holding the same number of crew members.
To avoid system conflicts, no module may contain two astronauts sharing the same mission code.

For each module, the synchronization gap is defined as the difference between the highest and lowest mission codes present.
The total mission instability is the sum of synchronization gaps across all modules.

Your task is to assign astronauts to modules such that the total instability is minimized.
If no valid assignment satisfies all conditions, return -1.

## Examples

### 1

#### Input
4 2
1 2 1 4  

#### Output  
4

#### Explanation

A valid distribution:  
- [1, 2] → incompatibility = 1  
- [1, 4] → incompatibility = 3  

Total = 4.


### 2

#### Input
6 3
5 3 3 6 3 3  

#### Output  
-1

#### Explanation

Each group must contain 2 elements, but duplicates make this impossible.  
Hence return -1.

## Input Format

- Integer array `nums`  
- Integer `k`  
- nums.length is divisible by k  
- 1 ≤ nums.length ≤ 16  
- 1 ≤ nums[i] ≤ nums.length

## Output Format

- Return the minimum total incompatibility, or -1 if no valid grouping exists.

## Constraints

- 1 ≤ nums.length ≤ 16  
- 1 ≤ k ≤ nums.length  
- nums.length % k == 0  
- Answer fits in 32-bit signed integer

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

DynamicProgramming
