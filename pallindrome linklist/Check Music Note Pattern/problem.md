## Title  
Check Music Note Pattern  

## Slug  
check-music-note-pattern  

## Difficulty  
Easy  

## Description  

A composer records a melody as a linked list of note values.  
Your task is to determine whether the musical pattern is `palindromic` — it sounds the same when played in reverse.  

Return `true` if the melody is reversible, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
3 6 9 6 3  

#### Output  
true  

#### Explanation  
The pattern `3 → 6 → 9 → 6 → 3` is identical backward.  

### 2  

#### Input  
4  
5 7 8 5  

#### Output  
false  

#### Explanation  
The reverse melody differs, so it’s not a palindrome.  

## Input Format  
- First line: integer n — number of notes.  
- Second line: list of notes.  

## Output Format  
Return `true` if the melody is palindromic, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
