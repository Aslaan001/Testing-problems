## Title  
Check Network Packet Sequence  

## Slug  
check-network-packet-sequence  

## Difficulty  
Easy  

## Description  

A network transmits packets represented by IDs in a linked list.  
You must check whether the transmission pattern is `palindromic`.  

Return `true` if identical backward, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
4 8 9 8 4  

#### Output  
true  

#### Explanation  
The packet IDs are mirrored perfectly.  

### 2  

#### Input  
4  
1 2 3 4  

#### Output  
false  

#### Explanation  
The sequence changes in reverse.  

## Input Format  
- First line: integer n — number of packets.  
- Second line: packet IDs.  

## Output Format  
Return `true` if palindromic, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
