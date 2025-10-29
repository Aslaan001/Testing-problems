## Title

Unique Animal Sighting

## Slug

unique-animal-sighting

## Difficulty

Medium

## Description

You are tracking animals in the jungle, each represented by a unique integer ID.  
Some animals were sighted multiple times.  

Find the `index of the first animal` that was sighted `only once`.  

If no such animal exists, return `-1`.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Animal 5 was seen once → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Animal 3 seen once → index 4.

## Input Format  

- First line: integer `n` — number of sightings.  
- Second line: `n` integers `arr[i]` — animal IDs.

## Output Format  

- A single integer — index of first unique animal, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
