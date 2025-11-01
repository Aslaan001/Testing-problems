## Title
Reverse Playlist Section

## Slug
reverse-playlist-section

## Difficulty
Medium

## Description

A DJ has a playlist of songs in a queue.  
You are asked to reverse the order of songs between positions `m` and `n`.

`Details:`  
* Positions are 1-indexed.  
* It is guaranteed that `1 <= m <= n <= total songs`.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Original queue: `1 -> 2 -> 3 -> 4 -> 5`.  
Reverse section 2–4 → `4 -> 3 -> 2`.  
New order: `1 -> 4 -> 3 -> 2 -> 5`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
Full playlist reversed.

### 3
#### Input
1  
5  
1 1  

#### Output
5  

#### Explanation
Only one song, no change.

## Input Format
- First line: integer `n` — number of songs.  
- Second line: `n` integers representing song IDs.  
- Third line: two integers `m` and `n` — start and end positions.

## Output Format
Print all song IDs after the reversal.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= song.id <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
