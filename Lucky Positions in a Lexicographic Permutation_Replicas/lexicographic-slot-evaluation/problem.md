## Title
Lexicographic Slot Evaluation

## Slug
lexicographic-slot-evaluation

## Difficulty
Hard

## Description
In analytical studies involving ordered datasets, lexicographic slot evaluation is used to identify meaningful alignments between positional indices and stored values.

A system considers all permutations of a fixed sequence of integers arranged in lexicographical order.
Each permutation represents a unique ordering scenario that may arise in ranking systems, scheduling pipelines, or combinatorial indexing mechanisms.

Given a specific rank within this ordered permutation space, the task is to inspect the resulting arrangement and identify positions that satisfy a dual constraint.
A position qualifies only if both the index itself and the value placed at that index belong to a predefined category of numerically significant values.

If the requested permutation rank exceeds the total number of valid permutations, the evaluation terminates immediately.
Otherwise, the objective is to count how many positions meet the required alignment condition in the selected permutation.


## Examples

### 1
#### Input
7 4  

#### Output
1  

#### Explanation
The 4th lexicographical permutation of numbers from 1 to 7 is:
1 2 3 4 6 7 5  

Only position 4 satisfies the condition that both the index and the value are lucky numbers.

### 2
#### Input
4 7  

#### Output
1  

#### Explanation
The 7th lexicographical permutation of numbers from 1 to 4 is:
2 1 3 4  

Only position 4 satisfies the required condition.

## Input Format
- The input contains two integers n and k:
  - n — the number of elements in the permutation
  - k — the lexicographical index of the permutation

## Output Format
- If the k-th permutation of numbers from 1 to n does not exist, output `-1`.
- Otherwise, output a single integer — the number of positions i such that both i and ai are lucky numbers.

## Constraints
- 1 ≤ n ≤ 10^9  
- 1 ≤ k ≤ 10^9  

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
maths, greedy, hackwithinfy

## Company
infosys
