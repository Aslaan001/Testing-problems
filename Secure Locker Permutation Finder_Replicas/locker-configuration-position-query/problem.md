## Title
Locker Configuration Position Query

## Slug
locker-configuration-position-query

## Difficulty  
Medium  

## Description

In a restricted facility control platform, lockers are identified using sequential numeric labels starting from 1 up to a defined maximum.

To generate deterministic access schedules, the system considers every possible ordering of these locker identifiers. All such orderings are sorted in strict lexicographical order and indexed starting from position one.

Given the total number of lockers and a specific rank value, the task is to determine which exact ordering appears at the requested position. The result must be computed directly without generating or storing all possible permutations, as the number of arrangements grows factorially.

The output must represent the locker identifiers in sequence form, accurately reflecting the ordering corresponding to the provided rank under lexicographical rules.
## Examples  

### 1  

#### Input  
AB  

#### Output  
Alpha  

#### Explanation  

The first senator belongs to Alpha and revokes the voting rights of the second senator.  
Only Alpha senators remain, so Alpha declares victory.

### 2  

#### Input  
ABB  

#### Output  
Beta  

#### Explanation  

The first senator from Alpha revokes one Beta senator.  
The remaining Beta senator then revokes the Alpha senator.  
Only Beta senators remain, so Beta declares victory.

## Input Format  

- A single line containing a string senate representing the factions of senators.

## Output Format  

Return a single string — "Alpha" or "Beta" — indicating the winning faction.

## Constraints  

1 ≤ senate.length ≤ 10000  
senate[i] is either 'A' or 'B'  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue. 