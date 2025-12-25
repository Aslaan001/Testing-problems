## Title

Metric Peak Position Evaluator

## Slug

metric-peak-position-evaluator

## Difficulty

Medium

## Description

In performance monitoring and analytical systems, streams of numerical measurements are continuously
evaluated to detect significant changes or anomalies. A common requirement is to identify positions
where a metric reaches a local maximum relative to its immediate neighbors, indicating potential
spikes, trend reversals, or noteworthy events. Boundary measurements are treated with implicit lower
limits to ensure consistent evaluation across the entire sequence. Given an array of measurements
with no equal adjacent values, the system must efficiently locate any one index representing such a
local maximum. To scale for large datasets, the detection logic is expected to operate in
logarithmic time, reflecting real-world constraints in high-throughput monitoring and signal
analysis systems.

## Examples

### 1

#### Input

4  
1 2 3 1

#### Output

2

#### Explanation

The value 3 is greater than both of its neighbors, so index 2 is a valid peak.

### 2

#### Input

7  
1 2 1 3 5 6 4

#### Output

5

#### Explanation

There are two valid peaks:
- Index 1 with value 2  
- Index 5 with value 6  

Either index is a valid answer.

## Input Format

- First line contains an integer n, the number of elements in the array.
- Second line contains n space-separated integers representing the array nums.

## Output Format

- Return a single integer representing the index of any peak element.

## Constraints

- 1 ≤ n ≤ 1000  
- -2^31 ≤ nums[i] ≤ 2^31 - 1  
- nums[i] is not equal to nums[i + 1] for all valid i

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company


