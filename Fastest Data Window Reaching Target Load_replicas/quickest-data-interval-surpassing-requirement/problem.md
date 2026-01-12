## Title
Quickest Data Interval Surpassing Requirement

## Slug
quickest-data-interval-surpassing-requirement

## Difficulty  
Hard  

## Description

In a high-throughput data processing service, numerical workload deltas are recorded sequentially to represent changes in system demand over time.

Each recorded value may contribute positively or negatively to the overall workload, reflecting bursts of activity, idle periods, throttling, or recovery phases.

A *window* is defined as a contiguous subarray of these recorded values. Such a window represents a continuous operational interval whose cumulative workload is the sum of its elements.

Engineering teams are tasked with identifying the **fastest possible interval** in which the accumulated workload reaches or exceeds a predefined operational target `k`. This requirement commonly arises in scenarios such as SLA enforcement, alert triggering, capacity validation, or risk assessment.

The window must be non-empty and strictly contiguous. If multiple windows satisfy the workload requirement, the one with the smallest length is considered optimal, as it represents the quickest escalation to the target state.

If no contiguous interval in the data stream achieves a total workload of at least `k`, the system must explicitly report failure by returning `-1`.

Your task is to compute the length of this shortest valid window while handling large input sizes efficiently and accounting for negative workload fluctuations.
## Examples  

### 1  

#### Input  
1  
1  
1  

#### Output  
1  

### 2  

#### Input  
2  
1 2  
4  

#### Output  
-1  

### 3  

#### Input  
3  
2 -1 2  
3  

#### Output  
3  

## Input Format  

- The first line contains an integer n — the number of time steps  
- The second line contains n space-separated integers representing nums  
- The third line contains an integer k  

## Output Format  

Return a single integer — the length of the shortest valid subarray.  
If no such subarray exists, return -1.

## Constraints  

1 ≤ n ≤ 100000  
-100000 ≤ nums[i] ≤ 100000  
1 ≤ k ≤ 1000000000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.