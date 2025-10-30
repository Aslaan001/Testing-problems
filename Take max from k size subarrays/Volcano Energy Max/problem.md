## Title
Volcano Energy Max

## Slug
volcano-energy-max

## Difficulty
Easy

## Description
During a volcano study, scientists recorded energy spikes from eruptions.  
Find the `maximum total energy` from any `k` consecutive spikes`.

Return that energy total.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Energy bursts: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — number of spikes.  
- Second line: `n` integers — energy values.  
- Third line: integer `k` — window size.

## Output Format
One integer — maximum total energy.

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
