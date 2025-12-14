## Title
Aligned Nicknames of Twin Historians

## Slug
aligned-nicknames-of-twin-historians

## Difficulty
Hard

## Description
In a scenario known as aligned nicknames of twin historians, two siblings with identical training maintain official names written in uppercase letters.
The elder sibling has a name of length N, while the younger has a longer name of length M, where N does not exceed M.

Each sibling is to receive a nickname.
The elder sibling’s nickname may be formed by rearranging the letters of the original name in any order.
The younger sibling’s nickname is formed by first rearranging their original name and then removing exactly M − N characters while keeping the order of the remaining ones.

Both nicknames must end up having exactly N characters.
They must also satisfy a synchronization rule: at every position, the younger sibling’s character must be either equal to the elder’s character or the immediate alphabetical successor of it, if such a successor exists.

Determine how many distinct pairs of nicknames can be formed under these rules.
Return the answer modulo 998244353.

## Examples

### 1
#### Input
3 4  
AMA  
ANAB

#### Output
9

### 2
#### Input
5 8  
BINUS  
BINANUSA

#### Output
120

## Input Format
- First line: integers N and M  
- Second line: string A of length N  
- Third line: string B of length M  
All characters are uppercase English letters.

## Output Format
Return a single integer — the number of valid nickname pairs (A′, B′) modulo 998244353.

## Constraints
1 ≤ N ≤ M ≤ 200000  
All strings contain only uppercase letters.

## Time Limit
1 second

## Memory Limit
1024 megabytes

## Tags
dynamic-programming, hackwithinfy

## Company
infosys
