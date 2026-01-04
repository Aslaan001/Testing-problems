## Title
Enterprise Information Awareness Audit

## Slug
enterprise-information-awareness-audit

## Difficulty
Medium

## Description

Modern enterprises actively track how sensitive internal information propagates across teams over time. Each day represents a discrete reporting interval during which employees may acquire, share, or lose awareness of a confidential update, policy change, or operational alert.

On the first day, a single employee becomes aware of the confidential information. After learning the information, each individual follows strict compliance rules governing when they are allowed to share it and how long they are permitted to retain it.

An individual begins sharing the information with exactly one new employee per day only after a fixed delay period has elapsed since they first learned it. Additionally, each individual permanently forgets the information after a specified number of days, after which they can no longer share or contribute to further dissemination.

The organization wants to understand the total awareness footprint of the confidential information at a given point in time. Your task is to determine how many individuals still retain the information at the end of day n, considering all sharing delays, forgetting rules, and retention constraints.

Because the number of aware individuals can grow rapidly, the final count must be computed using modular arithmetic.

## Examples  

### 1  

#### Input  
6  
2  
4  

#### Output  
5  

#### Explanation  

Day 1: One person knows the information.  
Day 2: No new sharing occurs.  
Day 3: The first person shares the information with one new person.  
Day 4: The first person shares the information again.  
Day 5: The first person forgets the information, while another person shares it.  
Day 6: Two people share the information, resulting in five people knowing it.  

### 2  

#### Input  
4  
1  
3  

#### Output  
6  

#### Explanation  

Day 1: One person knows the information.  
Day 2: The information is shared with one new person.  
Day 3: Two people share the information with two new people.  
Day 4: One person forgets the information, while others continue sharing.  

## Input Format  

- The first line contains an integer n — the total number of days.  
- The second line contains an integer delay — the number of days before a person starts sharing.  
- The third line contains an integer forget — the number of days after which a person forgets the information.  

## Output Format  

Return a single integer — the number of people who know the information at the end of day n, modulo 10^9 + 7.

## Constraints  

2 ≤ n ≤ 1000  
1 ≤ delay < forget ≤ n  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

dynamic-programming, queue  
