## Title
Corporate Vehicle Distribution Patterns

## Slug
corporate-vehicle-distribution-patterns

## Difficulty
Hard

## Description
In large corporate environments, corporate vehicle distribution patterns plays an important role in maintaining order, branding consistency, and operational discipline.

An organization manages a fixed-length parking row allocated exclusively to company-owned vehicles drawn from a limited set of approved brands.
Every parking position must be occupied, and the total number of vehicles always exceeds the number of available spaces, ensuring no gaps appear in the lineup.

For visual uniformity and ease of inspection, management mandates that there must exist a contiguous block of exactly n vehicles belonging to the same brand somewhere within the row.
Outside this block, vehicles may belong to any of the permitted brands, subject only to occupancy constraints.

Each distinct assignment of brands to parking positions represents a unique configuration.
The objective is to determine the total number of valid configurations that satisfy the continuity requirement under the given constraints.


## Examples

### 1
#### Input
3  

#### Output
24  

#### Explanation
For n = 3, the parking lot has 4 parking spaces.  
Each valid arrangement contains exactly 3 consecutive cars of the same brand.

## Input Format
- The input contains a single integer n — the required number of consecutive cars of the same brand.

## Output Format
Return a single integer — the number of valid ways to fill the parking lot.

## Constraints
- 3 ≤ n ≤ 30  

## Time Limit
0.5 seconds

## Memory Limit
64 megabytes


## Tags
maths, hackwithinfy

## Company
infosys
