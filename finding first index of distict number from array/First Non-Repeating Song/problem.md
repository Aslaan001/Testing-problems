## Title

First Non-Repeating Song

## Slug

first-nonrepeating-song

## Difficulty

Medium

## Description

You are given a playlist represented as an array of song IDs.  
Some songs are played multiple times, while others are unique.  

Your task is to find the `index of the first song` that is played `exactly once`.  

Return its 0-based index. If all songs are repeated, return `-1`.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Songs 2 and 3 repeat.  
Song 5 appears once — first unique song at index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Songs 1 and 2 repeat; 3 is unique → index 4.

## Input Format  

- First line: integer `n` — number of songs in the playlist.  
- Second line: `n` integers `arr[i]` — song IDs.

## Output Format  

- A single integer — the index of the first non-repeating song, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
