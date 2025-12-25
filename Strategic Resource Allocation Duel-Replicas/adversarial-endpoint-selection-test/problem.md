## Title

Adversarial Endpoint Selection Test

## Slug

adversarial-endpoint-selection-test

## Difficulty

Medium

## Description

In a controlled decision experiment, two agents interact with a finite array of     numerical
resources arranged in a single line. During each round, exactly one asset may be taken     from
either end of the array, after which it is removed from further consideration. Each     agent
accumulates the value of the resources they claim. Assuming both sides apply perfect     decision-
making logic, the objective is to determine whether the agent who moves first can     guarantee a
favorable final outcome.

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
