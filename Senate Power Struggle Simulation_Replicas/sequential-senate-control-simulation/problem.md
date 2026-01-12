## Title
Sequential Senate Control Simulation

## Slug
sequential-senate-control-simulation

## Difficulty  
Medium  

## Description

In a legislative decision making system, members are divided into two opposing factions and participate in a structured decision process conducted over multiple rounds.

Each participant belongs exclusively to one faction and acts in a fixed left to right order during every round. As long as a participant retains voting rights, they may take exactly one action when their turn arrives.

An action consists of revoking the voting rights of a single participant from the opposing faction. Once voting rights are revoked, the affected participant is permanently removed from all current and future decision rounds.

The process continues iteratively across rounds until all remaining participants with voting rights belong to the same faction. At that point, the process terminates immediately and the remaining faction is declared the winner.

All participants are assumed to act strategically and optimally to maximize the likelihood of victory for their own faction. The objective is to determine which faction will ultimately prevail based on the initial ordering of participants.
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