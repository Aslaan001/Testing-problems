## Title

Find the Missing Packet ID

## Slug

find-missing-packet-id

## Difficulty

Easy

## Description

A data stream sends packets labeled with non-negative IDs.  
Some packets are missing during transmission.  

Given the list of received packet IDs, find the smallest packet ID that wasn’t received — the `MEX` of the list.

## Examples

### 1

#### Input

5  
0 1 2 4 5

#### Output
3

#### Explanation
Packet IDs 0,1,2,4,5 received.  
Packet `3` is missing.

### 2

#### Input

4  
1 0 2 3

#### Output
4

#### Explanation
Packets 0–3 received.  
Next expected is `4`.

## Input Format

- First line: integer `n` — number of packets received.  
- Second line: `n` integers `arr[i]` — packet IDs.

## Output Format

- A single integer — the missing packet ID.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
