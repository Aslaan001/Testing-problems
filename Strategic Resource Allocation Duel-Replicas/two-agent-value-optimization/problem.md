## Title

Two-Agent Value Optimization

## Slug

two-agent-value-optimization

## Difficulty

Medium

## Description

A competitive exercise models how two decision-makers alternately extract value from a     linear
collection of quantified items. Only boundary elements are accessible at any moment,     forcing
each choice to influence the options available in subsequent turns. Since both     agents optimize
their selections, the analysis focuses on whether the initial actor can     ensure at least a non-
losing result by the time all items are consumed.

## Examples

### 1

#### Input

3
1 5 2

#### Output

NO

#### Explanation

Analyst A can start by choosing either 1 or 2.  
Regardless of this choice, Analyst B can then select 5, gaining a decisive advantage.

At the end of the simulation, Analyst B’s total allocation exceeds Analyst A’s, so Analyst A cannot win under optimal play.

### 2

#### Input

4
1 5 233 7

#### Output

YES

#### Explanation

Analyst A begins by selecting 1.  
No matter whether Analyst B chooses 5 or 7, Analyst A will then be able to select 233.

This guarantees Analyst A a higher total allocation value by the end of the simulation, resulting in a win.

## Input Format

- A single integer array nums representing resource unit values arranged linearly

## Output Format

- Return true if Analyst A can win the simulation  
- Return false otherwise

## Constraints

- 1 ≤ nums.length ≤ 20  
- 0 ≤ nums[i] ≤ 10^7

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

dynamic-programming

## Company

snapchat
