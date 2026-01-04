## Title
Certified Prime Interval Audits

## Slug
certified-prime-interval-audits

## Difficulty
Medium

## Description

Large-scale enterprise systems continuously collect numeric indicators from distributed components such as services, databases, and infrastructure layers. Each recorded value represents a sampled operational metric captured during a fixed observation window.

Within this monitoring framework, certain values are formally recognized as certified metrics. A metric qualifies as certified if it satisfies a strict mathematical validation rule: it must be a prime number, ensuring deterministic uniqueness and integrity in analytical workflows.

Analysts evaluate contiguous observation windows over the recorded metric sequence to ensure regulatory and internal compliance. A window is considered compliant only when it contains at least two certified metrics and the operational deviation between the highest and lowest certified values within that window does not exceed a predefined tolerance threshold k.

It is important to note that non-certified values may appear inside a window but are ignored for compliance evaluation. Only certified metrics influence the range constraint.

Your task is to compute the total number of contiguous windows that satisfy these certification and range constraints, enabling automated compliance reporting across the monitoring dataset.

## Examples  

### 1  

#### Input  
3  
1 2 3  
1  

#### Output  
2  

#### Explanation  
The valid range-compliant subarrays are:  
[2, 3] and [1, 2, 3].  

Both subarrays contain the certified values 2 and 3, and their difference is 1, which is within the allowed threshold.  

### 2  

#### Input  
4  
2 3 5 7  
3  

#### Output  
4  

#### Explanation  
The range-compliant subarrays are:  
[2, 3], [2, 3, 5], [3, 5], and [5, 7].  

Each subarray contains at least two certified values, and the maximum difference among them does not exceed 3.  

## Input Format  

- The first line contains an integer n — the number of recorded readings.  
- The second line contains n space-separated integers representing the readings.  
- The third line contains an integer k — the maximum allowed range threshold.  

## Output Format  

Return a single integer — the total number of range-compliant subarrays in nums.  

## Constraints  

1 ≤ n ≤ 50000  
1 ≤ nums[i] ≤ 50000  
0 ≤ k ≤ 50000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

array, queue.
