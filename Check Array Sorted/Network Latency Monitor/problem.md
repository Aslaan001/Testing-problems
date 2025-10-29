## Title
Network Latency Monitor

## Slug
network-latency-monitor

## Difficulty
Easy

## Description
Latency probes are logged in milliseconds as `arr[]`. For a congestion alert, confirm that values do not decrease across samples. Determine if `arr[]` is in `non-decreasing order`. Print `true` if yes, otherwise `false`.

### Example 1
#### Input
6  
10 10 12 12 12 20
#### Output
true

### Example 2
#### Input
6  
10 12 11 13 14 15
#### Output
false

## Input Format
- `n` — sample count  
- `arr[]` — latencies

## Output Format
`true` or `false`

## Constraints
1 ≤ n ≤ 10⁶  
1 ≤ arr[i] ≤ 10⁶

## Tags
arrays, sorting
