## Title
A Social media analyst ranking posts by engagement signals

## Slug
a-social-media-analyst-ranking-posts-by-engagement-signals

## Difficulty
Medium

## Description

a social media analyst ranking posts by engagement signals. Each item in the
array represents a measurable value relating to that domain. The influence index
is defined as the maximum h such that at least h items have value ≥ h, while the
remaining items have value ≤ h. Determine this maximum index.

## Examples

### 1

#### Input
5
3 0 6 1 5

#### Output
3

#### Explanation
There are 3 papers with at least 3 citations each.
The remaining papers have fewer than or equal to 3 citations.

### 2

#### Input
3
1 3 1

#### Output
1

#### Explanation
Only one paper has at least one citation.

## Input Format

First line contains an integer n — the number of papers.
Second line contains n space-separated integers representing the citation counts.

## Output Format

Return the H-index value.

## Constraints

1 ≤ n ≤ 5000
0 ≤ citations[i] ≤ 1000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sorting, counting, simulation, research-analysis
