## Title
Maximum Stability Window in Sensor Streams

## Slug
maximum-stability-window-in-sensor-streams

## Difficulty  
Medium  

## Description

In a real time telemetry analysis system, numerical readings are continuously captured from sensors and stored sequentially for analysis.

Operational requirements dictate that a sequence of readings is considered stable only when the difference between the highest and lowest values within that sequence remains within a predefined tolerance limit. This constraint ensures reliability and consistency in downstream analysis and decision making.

A segment refers to any contiguous subset of the recorded readings. Such a segment represents an uninterrupted monitoring interval during which system behavior is evaluated.

The objective is to identify the longest possible contiguous segment where all readings satisfy the stability condition imposed by the tolerance limit. Segments that violate this condition at any point are considered invalid.

The analysis must efficiently handle large volumes of sensor data and accurately compute the maximum length of a valid stability preserving segment under the given constraints.
## Examples  

### 1  

#### Input  
4  
8 2 4 7  
4  

#### Output  
2  

#### Explanation  

The longest stable segments are [2, 4] and [4, 7], each having a maximum difference within the allowed limit.

### 2  

#### Input  
6  
10 1 2 4 7 2  
5  

#### Output  
4  

#### Explanation  

The segment [2, 4, 7, 2] has a maximum difference of 5, which satisfies the limit, and has the maximum possible length.

### 3  

#### Input  
8  
4 2 2 2 4 4 2 2  
0  

#### Output  
3  

#### Explanation  

With a zero tolerance limit, only segments with identical values are valid.  
The longest such segment has length 3.

## Input Format  

- The first line contains an integer n — the number of sensor readings  
- The second line contains n space-separated integers representing the readings  
- The third line contains an integer limit  

## Output Format  

Return a single integer representing the length of the longest stable contiguous segment.

## Constraints  

1 ≤ n ≤ 100000  
1 ≤ nums[i] ≤ 1000000000  
0 ≤ limit ≤ 1000000000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.