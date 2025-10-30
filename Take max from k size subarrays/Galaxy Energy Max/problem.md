## Title
Galaxy Energy Max

## Slug
galaxy-energy-max

## Difficulty
Easy

## Description
In the distant galaxy of `Orion Prime`, each energy station emits a numeric charge.  
You must find the `maximum total energy` produced by any `k` consecutive stations`.

Return the total maximum energy output.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Energy clusters: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of stations.  
- Second line: `n` integers — energy values.  
- Third line: integer `k` — size of cluster.

## Output Format
Single integer — maximum total energy.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ energy[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
