## Title
Vault Key Engineering with Prime Limits

## Slug
vault-key-engineering-with-prime-limits

## Difficulty  
Hard  

## Description

In a high security authentication system, numeric keys are generated using prime numbers as fundamental building blocks.

Each key is defined as a positive integer composed of prime factors, where the total number of prime factors used, including repetitions, cannot exceed a given upper limit. Within this constraint, keys are evaluated based on the number of special divisors they produce.

A divisor is considered special if it is divisible by every prime factor used in the construction of the key. Only divisors that satisfy this requirement contribute to the special divisor count.

The objective is to determine how prime factors should be distributed when constructing a key so that the number of special divisors is as large as possible. This optimization must be performed before applying modular arithmetic.

Because the allowed number of prime factors can be extremely large, the final result must be returned modulo a fixed constant to remain within computational limits.
## Examples  

### 1  

#### Input  
2  
0 2  
1 3  

#### Output  
3  

#### Explanation  

At time 0, only the starting cell is accessible.  
Movement becomes possible only when the water level reaches 3, at which point all required cells are flooded and connected.

### 2  

#### Input  
5  
0 1 2 3 4  
24 23 22 21 5  
12 13 14 15 16  
11 17 18 19 20  
10 9 8 7 6  

#### Output  
16  

#### Explanation  

The team must wait until the water level reaches 16 so that a continuous path exists from the start to the destination.

## Input Format  

- The first line contains an integer n — the size of the grid  
- The next n lines each contain n space-separated integers representing the elevation grid  

## Output Format  

Return a single integer representing the minimum time required to reach the bottom-right cell.

## Constraints  

1 ≤ n ≤ 50  
0 ≤ grid[i][j] < n²  
Each elevation value is unique  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.