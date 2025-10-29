## Title

First Dominant Planet

## Slug

first-dominant-planet

## Difficulty

Medium

## Description

You are analyzing planetary masses in a distant solar system represented as an array.  
Each integer indicates the mass of a planet in sequential orbit.

Find the first dominant planet index i such that:

- The sum of all previous planet masses is less than mass[i].  
- The sum of all following planet masses is less than mass[i].

If no such planet exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
