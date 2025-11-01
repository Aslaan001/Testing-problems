## Title
DNA Strand Mutation

## Slug
dna-strand-mutation

## Difficulty
Medium

## Description
In the lab of `BioLink`, a DNA strand is modeled as a chain of nucleotide nodes.  
A mutation requires swapping the `kth base from the start` and the `kth base from the end` to maintain genetic symmetry.  

Return the updated DNA strand chain.

## Examples
### 1 
#### Input
6  
1 3 2 4 5 6  
2

#### Output
1 5 2 4 3 6

#### Explanation
Swapped 2nd base from start (`3`) with 2nd from end (`5`).

## Input Format
- First line: integer `n` — number of nucleotide nodes.  
- Second line: `n` integers — base values.  
- Third line: integer `k`.

## Output Format
Return the mutated DNA strand.

## Constraints
- 1 ≤ n ≤ 10^5  
- 1 ≤ k ≤ n  
- 0 ≤ node.val ≤ 100

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, arrays
