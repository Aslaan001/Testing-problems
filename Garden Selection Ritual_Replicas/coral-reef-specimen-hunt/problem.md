## Title
Coral Reef Specimen Hunt

## Slug
coral-reef-specimen-hunt

## Difficulty
Hard

## Description
A long observatory holds n used satellites lined from left to right.  
Each satellite carries a telemetry score ai.

An engineer wants to salvage exactly m satellites while proceeding strictly from the left hanger toward the right.  
When they pass any satellite, they may either claim it or allow it to remain.  
However, the i-th satellite they claim must have telemetry at least bi.

Before the operation, they may optionally install one test satellite once:  
they may add a single new satellite of any integer telemetry k at any position  
(before the first, after the last, or between satellites).

Your task is to determine the smallest integer k such that, after adding this test satellite,  
it becomes possible to salvage m satellites in valid order.  
If salvage is already possible without the test unit, return 0.  
If no test satellite helps, return −1.
## Examples

### 1
#### Input
9 5  
3 5 2 3 3 5 8 1 2  
4 6 2 4 6

#### Output
6

### 2
#### Input
6 3  
1 2 6 8 2 1  
5 4 3

#### Output
3

## Input Format  
A line with integers n and m  
A line with n integers a1 … an representing beauty values  
A line with m integers b1 … bm representing required minimum beauty for each chosen flower

## Output Format
For every test case, Return the minimum integer k that guarantees a valid collection of m flowers.  
If no additional flower is needed, Return 0.  
If creating any flower cannot help, Return −1.

## Constraints  
1 ≤ m ≤ n ≤ 2×10⁵  
1 ≤ ai ≤ 10⁹  
1 ≤ bi ≤ 10⁹  
Sum of all n across test cases ≤ 2×10⁵

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
dynamic-programming, hackwithinfy

## Company
infosys
