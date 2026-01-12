## Title
Alphabetically Minimal Output After Text Corrections

## Slug
alphabetically-minimal-output-after-text-corrections

## Difficulty  
Medium  

## Description

In a log ingestion system, characters are recorded sequentially exactly as they are produced. During this process, special correction markers may appear to indicate that previously recorded data must be adjusted.

Whenever a correction marker is encountered, the system immediately removes the marker itself along with one character that appears to its left in the recorded sequence. To ensure consistency and predictable outcomes, the character selected for removal is always the smallest possible character in alphabetical order among those eligible for deletion.

If multiple characters share the same smallest alphabetical value, the system may remove any one of them without affecting the validity of the result. This rule guarantees that the final reconstructed text is as small as possible in lexicographical order.

The correction process continues until all correction markers have been processed and removed from the sequence. The input is guaranteed to be valid, ensuring that a removable character always exists when a correction marker is applied.

The task is to simulate this correction workflow accurately and produce the final text output that is lexicographically minimal after all required removals are completed.
## Examples  

### 1  

#### Input  
aaba*  

#### Output  
aab  

#### Explanation  

One of the characters `'a'` to the left of `*` is removed.  
Removing the rightmost `'a'` results in the smallest possible string.  

### 2  

#### Input  
abc  

#### Output  
abc  

#### Explanation  

There are no correction markers, so the string remains unchanged.  

## Input Format  

- The first line contains an integer T — the number of test cases.  
- Each of the next T lines contains a string s.  

## Output Format  

For each test case, output the resulting string after all correction operations are applied.  

## Constraints  

1 ≤ T ≤ 10  
1 ≤ length of s ≤ 100000  
s contains only lowercase English letters and `*`  
All `*` characters can be successfully removed  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

priority-queue  