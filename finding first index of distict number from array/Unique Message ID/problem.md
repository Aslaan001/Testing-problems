## Title

Unique Message ID

## Slug

unique-message-id

## Difficulty

Medium

## Description

You are analyzing a chat log represented as an array of message IDs.  
Some messages were sent multiple times due to retries.  

Find the `index of the first message` that appears `exactly once`.  

Return `-1` if all messages are repeated.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Message IDs 2 and 3 repeat; message 5 appears once → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Only message 3 appears once → index 4.

## Input Format  

- First line: integer `n` — number of messages.  
- Second line: `n` integers `arr[i]` — message IDs.

## Output Format  

- A single integer — index of first unique message, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
