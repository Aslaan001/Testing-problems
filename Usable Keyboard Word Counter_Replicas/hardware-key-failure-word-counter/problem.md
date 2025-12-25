## Title

Hardware Key Failure Word Counter

## Slug

hardware-key-failure-word-counter

## Difficulty

Easy

## Description

A software check simulates typing text on a input device with limited functionality. By comparing
the characters used in each word against a list of disabled keys, the module determines which
tokens remain typeable. The final count reflects how many tokens can be produced using only the
remaining functional keys.

## Examples

### 1

#### Input

hello world  
ad

#### Output

1

#### Explanation

The word `world` cannot be typed because it contains the letter `d`, which is broken.  
Only `hello` can be typed.

### 2

#### Input

leet code  
lt

#### Output

1

#### Explanation

The word `leet` cannot be typed because it contains both `l` and `t`, which are broken.  
The word `code` can be typed successfully.

### 3

#### Input

leet code  
e

#### Output

0

#### Explanation

Both words contain the letter `e`, which is broken, so no word can be typed.

## Input Format

- First line contains a string `text` representing the words to be typed.
- Second line contains a string `brokenLetters` representing the broken keys.

## Output Format

- Return a single integer representing the number of words that can be fully typed.

## Constraints

- 1 ≤ length of text ≤ 10000  
- 0 ≤ length of brokenLetters ≤ 26  
- text consists of lowercase words separated by a single space  
- brokenLetters contains distinct lowercase English letters

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

string

## Company

quora
