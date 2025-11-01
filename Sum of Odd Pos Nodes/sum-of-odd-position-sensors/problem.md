## Title
Sum of Odd Position Sensors

## Slug
sum-of-odd-position-sensors

## Difficulty
Easy

## Description

In a high-tech laboratory, sensors are placed in a straight line to measure environmental changes.  
Each sensor records a signal value, and your task is to find the total signal of sensors located at `odd positions`.

Positions are `1-based`.

Return the total signal value from sensors at odd positions.

## Examples

### 1

#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Sensors at odd positions: 10, 30, 50.  
Sum = 10 + 30 + 50 = 90.

### 2

#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Sensors at odd positions: 5 and 25.  
Sum = 5 + 25 = 30.

## Input Format
- First line: integer `n` — the number of sensors.  
- Second line: `n` integers representing the sensor readings.

## Output Format
Return the total signal value of sensors at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ sensor.value ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
