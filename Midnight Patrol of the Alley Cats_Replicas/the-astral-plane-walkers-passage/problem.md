## Title
The Astral Plane Walker’s Passage

## Slug
the-astral-plane-walkers-passage

## Difficulty
Hard

## Description
Every night, a walker walks along a long astral plane consisting of n numbered checkpoints.

There are m entities living within this region.
Each one roams only during a specific part of the night:
entity i can be found from checkpoint li to checkpoint ri, inclusive.

Whenever the walker reaches a checkpoint, they may choose to place a signal there.
All entities currently present at that checkpoint immediately respond to it.
However, each entity must be triggered at most once — interacting twice causes failure.

The goal is to maximize the number of distinct entities safely interacted with.
The chosen checkpoints must satisfy:

• No entity's roaming interval contains more than one chosen checkpoint,
• And the total number of entities triggered exactly once is maximized.

Your task is to compute the highest number of entities that can be safely handled.
## Examples

### 1
#### Input
15 6  
2 10  
3 5  
2 4  
7 7  
8 12  
11 11

#### Output
5

### 2
#### Input
1000 1  
1 1000

#### Output
1

## Input Format
A line with integers n and m  
m lines follow, each with two integers li and ri describing the roaming interval of a cat.

## Output Format
Return the maximum number of cats that can be fed exactly once without violating the constraints.

## Constraints 
1 ≤ n ≤ 10⁶  
1 ≤ m ≤ 2⋅10⁵  
1 ≤ li ≤ ri ≤ n  
Sum of all n across test cases ≤ 10⁶  
Sum of all m across test cases ≤ 2⋅10⁵

## Time Limit
3 seconds

## Memory Limit
512 megabytes

## Tags
dynamic-programming, hackwithinfy

## Company
infosys
