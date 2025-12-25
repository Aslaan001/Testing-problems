## Title

Land Adjacency Region Analysis

## Slug

land-adjacency-region-analysis

## Difficulty

Medium

## Description

In geospatial analytics and remote sensing platforms, terrain data is often represented as a binary
grid distinguishing land from non-land areas. Accurate identification of connected land regions is
critical for environmental assessment, resource planning, and infrastructure analysis. Cells
representing land are considered connected only when they share a direct horizontal or vertical
boundary, reflecting realistic adjacency constraints. Given a fully bounded grid, the system must
traverse the terrain data to determine how many independent land regions exist. Each region is
counted once regardless of its size or shape. This task mirrors practical challenges in spatial data
processing, image segmentation, and geographic information systems where component detection is
essential.

## Examples

### 1

#### Input

4 5  
1 1 1 1 0  
1 1 0 1 0  
1 1 0 0 0  
0 0 0 0 0  

#### Output

1

#### Explanation

All land cells are connected through horizontal or vertical paths, forming a single landmass cluster.

### 2

#### Input

4 5  
1 1 0 0 0  
1 1 0 0 0  
0 0 1 0 0  
0 0 0 1 1  

#### Output

3

#### Explanation

There are three separate landmass clusters that are not connected to each other.

## Input Format

- First line contains two integers `m` and `n` representing the number of rows and columns  
- The next `m` lines each contain `n` space-separated values (`0` or `1`) representing the grid

## Output Format

- Return a single integer representing the number of distinct landmass clusters

## Constraints

- 1 ≤ m, n ≤ 300  
- Each grid cell is either `0` or `1`

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

breadth-first-search , depth-first-search.

## Company


