## Title

Shifting Belt Markings

## Slug

shifting-belt-markings

## Difficulty

Easy

## Description

This task is framed around Shifting Belt Markings.

You are given two sequences represented as strings `s` and `goal`. A rotation action consists of taking the first character of `s` and moving it to the end, similar to the rotational movement seen in shifting belt markings.

For example, if `s = "abcde"`, applying one rotation results in `"bcdea"`.

Your objective is to determine whether repeated rotations of `s` can eventually match the target pattern `goal`. Return `true` if such a transformation is possible, otherwise return `false`.


## Examples

### 1

#### Input

s = "abcde", goal = "cdeab"

#### Output

true

### 2

#### Input

s = "abcde", goal = "abced"

#### Output

false

### 3

#### Input

s = "aaaa", goal = "aaaa"

#### Output

true

## Input Format

- Two lines of input, each containing a string `s` and `goal`.

## Output Format

- Return `true` if `s` can be rotated to match `goal`, otherwise return `false`.

## Constraints

- 1 ≤ s.length, goal.length ≤ 100
- s and goal consist of lowercase English letters.

## Time Limit

1 second

## Memory Limit

256 MB

## Tags

string
