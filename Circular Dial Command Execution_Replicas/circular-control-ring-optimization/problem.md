## Title

Circular Control Ring Optimization

## Slug

circular-control-ring-optimization

## Difficulty

Hard

## Description

In secure operational environments, rotary input mechanisms are often used to limit unauthorized
access while providing precise control over command execution. Such systems rely on circular
interfaces where selectable options are arranged in a continuous loop. Operators must carefully
rotate the mechanism in either direction to align the desired instruction with a fixed reference
point before confirming execution. Each rotation and confirmation incurs a measurable operational
cost. Given a predefined sequence of required instructions, engineers must compute the minimum
number of actions needed to complete the entire sequence efficiently. This problem reflects real-
world considerations in hardware interface optimization, control system design, and human-machine
interaction efficiency.

## Examples

### 1

#### Input

godding  
gd

#### Output

4

#### Explanation

The first command character `g` is already aligned, so only one step is needed to press the button.  
For the next character `d`, the dial is rotated anticlockwise by two positions and then the button is pressed.

Total steps required are 4.

### 2

#### Input

godding  
godding

#### Output

13

## Input Format

- First line: string `ring` representing the circular dial  
- Second line: string `key` representing the command sequence

## Output Format

- Return a single integer representing the minimum number of steps required to execute the full command sequence

## Constraints

- 1 ≤ length of `ring`, `key` ≤ 100  
- Both strings contain only lowercase English letters  
- The command sequence can always be executed using the dial

## Time Limit

1 second

## Memory Limit

512 MB

## Company

deshaw

## Tags

dynamic-programming, string
