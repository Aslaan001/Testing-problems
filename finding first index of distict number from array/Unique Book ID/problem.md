## Title

Unique Book ID

## Slug

unique-book-id

## Difficulty

Medium

## Description

A librarian keeps track of books using integer IDs.  
Some books are recorded multiple times by mistake.  

Find the `index of the first book` that appears `only once`.  

If all book IDs repeat, return `-1`.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Book 5 is unique and first appears at index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Book 3 appears once → index 4.

## Input Format  

- First line: integer `n` — number of book entries.  
- Second line: `n` integers `arr[i]` — book IDs.

## Output Format  

- A single integer — index of first unique book, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
