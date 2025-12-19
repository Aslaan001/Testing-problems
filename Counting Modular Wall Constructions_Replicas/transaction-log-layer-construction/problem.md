## Title
Transaction Log Layer Construction

## Slug
transaction-log-layer-construction

## Difficulty
Hard

## Description
In a real-world transaction log layer construction scenario, organizations must carefully enumerate all valid configurations to ensure compliance, scalability, and reliability.
    
A large-scale organization is planning a standardized physical structure composed of vertical segments arranged on a fixed-width grid.
Each segment is assembled by stacking identical rectangular units vertically within each column.

A construction plan is defined by explicitly choosing which grid coordinates (column index and vertical level) contain a unit.
The plan must use at least one unit and no more than the allowed maximum.

The total width of the structure is fixed, but each column may contain an arbitrary number of stacked units as long as the overall limit is respected.

Two construction plans are considered different if there exists at least one grid position where one plan places a unit and the other does not.

Your task is to compute how many distinct construction plans can be created under these operational constraints.
Since the total number of valid plans can be extremely large in real deployments, the final answer must be reported modulo 10^6 + 3.


## Examples

### 1
#### Input
5 1  

#### Output
5  

#### Explanation
With width 1, each brick simply stacks vertically, resulting in 5 possible walls.

### 2
#### Input
2 2  

#### Output
5  

#### Explanation
There are 5 distinct ways to place up to 2 bricks across 2 columns.

### 3
#### Input
3 2  

#### Output
9  

#### Explanation
The wall configurations include all arrangements using up to 3 bricks. 

## Input Format
- The input consists of two space-separated integers:
  - n — the maximum number of bricks allowed
  - C — the width of the wall (number of columns)

## Output Format
Return a single integer — the number of different walls that can be constructed, modulo `10^6 + 3`.

## Constraints
- 1 ≤ n ≤ 500000  
- 1 ≤ C ≤ 200000  

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
maths, hackwithinfy

## Company
infosys
