## Title

First Unique Sensor Reading

## Slug

first-unique-sensor-reading

## Difficulty

Medium

## Description

A sequence of sensor readings is recorded as integers.  
Some readings repeat due to environmental noise, while others are unique.  

Find the `index of the first reading` that occurs `exactly once`.  

Return the 0-based index, or `-1` if no unique reading exists.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7   

#### Output
2

#### Explanation

Reading 5 appears once → index 2.

### 2

#### Input

5  
1 1 2 2 3     

#### Output

4

#### Explanation

Reading 3 is unique → index 4.

## Input Format  


- First line: integer `n` — number of readings.  
- Second line: `n` integers `arr[i]` — sensor readings.

## Output Format  

- A single integer — the index of the first unique reading, or `-1`.
  

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
