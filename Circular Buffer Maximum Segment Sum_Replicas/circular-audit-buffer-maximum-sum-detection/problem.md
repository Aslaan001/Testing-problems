## Title
Circular Audit Buffer Maximum Sum Detection

## Slug
circular-audit-buffer-maximum-sum-detection

## Difficulty  
Medium  

## Description

In a large-scale payment gateway audit buffer, numerical measurements are continuously written into a fixed-size circular buffer to control memory usage and ensure constant-time inserts.

This buffer behaves as a logical ring: once the end is reached, incoming values overwrite from the beginning. The stored values may represent positive contributions (such as gains, throughput, or performance improvements) or negative impacts (such as losses, delays, or regressions).

A *segment* is defined as a contiguous sequence of entries extracted from this circular structure under strict operational rules:
- The segment must contain at least one recorded value.
- Each buffer position may be used no more than once within the same segment, ensuring the segment length never exceeds the buffer size.
- Due to the circular topology, a segment may start near the end of the buffer and continue at the beginning.

Formally, if a segment starts at index `i` and ends at index `j`, it includes the values:
`nums[i], nums[i+1], ..., nums[j]`, where indices advance modulo `n`.

From an analytics and decision-making perspective, such a segment represents a continuous operational interval whose aggregate impact is the sum of its values.

Your objective is to compute the **maximum possible sum** that can be obtained from any valid segment in the circular buffer. This value reflects the most favorable continuous interval observed by the system, accounting for wrap-around behavior and edge cases where all recorded values may be negative.
## Examples  

### 1  

#### Input  
4  
1 -2 3 -2  

#### Output  
3  

#### Explanation  

The maximum sum segment is [3], which gives a total sum of 3.

### 2  

#### Input  
3  
5 -3 5  

#### Output  
10  

#### Explanation  

The segment wraps around the buffer and includes the first and last elements: [5, 5].  
The sum of this segment is 10.

### 3  

#### Input  
3  
-3 -2 -3  

#### Output  
-2  

#### Explanation  

All values are negative, so the maximum sum segment consists of the single largest value [-2].

## Input Format  

- The first line contains an integer n — the number of elements in the buffer.  
- The second line contains n space-separated integers representing the buffer values.  

## Output Format  

Return a single integer — the maximum possible sum of a valid circular segment.

## Constraints  

1 ≤ n ≤ 30000  
-30000 ≤ nums[i] ≤ 30000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.