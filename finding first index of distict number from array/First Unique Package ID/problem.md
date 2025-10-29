## Title

First Unique Gene Marker

## Slug

first-unique-gene-marker

## Difficulty

Medium

## Description

A genetic sequencer outputs integer markers for detected gene fragments.  
Some markers appear repeatedly; a few are unique.  

Find the `index of the first gene marker` that appears `exactly once`.  

Return the 0-based index or `-1` if there is no unique marker.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7   

#### Output
2

#### Explanation

Marker 5 appears once → index 2.

### 2

#### Input

5  
1 1 2 2 3     

#### Output

4

#### Explanation

Marker 3 is unique → index 4.

## Input Format  


- First line: integer `n` — number of markers.  
- Second line: `n` integers `arr[i]` — marker IDs.

## Output Format  

- A single integer — the index of the first unique gene marker, or `-1`.
  

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
