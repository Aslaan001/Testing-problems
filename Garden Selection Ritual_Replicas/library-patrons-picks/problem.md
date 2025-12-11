## Title
Library Patron's Picks

## Slug
library-patrons-picks

## Difficulty
Hard

## Description
A long library shelf contains n books placed from left to right.  
Each book has a rating ai.

A reader wishes to borrow exactly m books while walking strictly from the leftmost shelf toward the right.  
When they stop at any book, they may either borrow it or skip it.  
However, the i-th book they borrow must have rating at least bi.

Before beginning, the librarian may optionally add one special volume exactly once:  
they may place a single new book of any integer rating k at any position on the shelf  
(before the first book, after the last book, or between existing books).

Your task is to determine the smallest integer k such that, after placing this book,  
it becomes possible to borrow m books in the required order.  
If the reader can already meet the requirements with no added book, return 0.  
If placing any book cannot help, return −1.
## Examples

### 1
#### Input
9 5  
3 5 2 3 3 5 8 1 2  
4 6 2 4 6

#### Output
6

### 2
#### Input
6 3  
1 2 6 8 2 1  
5 4 3

#### Output
3

## Input Format  
A line with integers n and m  
A line with n integers a1 … an representing beauty values  
A line with m integers b1 … bm representing required minimum beauty for each chosen flower

## Output Format
For every test case, Return the minimum integer k that guarantees a valid collection of m flowers.  
If no additional flower is needed, Return 0.  
If creating any flower cannot help, Return −1.

## Constraints  
1 ≤ m ≤ n ≤ 2×10⁵  
1 ≤ ai ≤ 10⁹  
1 ≤ bi ≤ 10⁹  
Sum of all n across test cases ≤ 2×10⁵

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
dynamic-programming, hackwithinfy

## Company
infosys
