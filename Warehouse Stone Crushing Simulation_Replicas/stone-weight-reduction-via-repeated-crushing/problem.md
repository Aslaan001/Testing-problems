## Title
Stone Weight Reduction via Repeated Crushing

## Slug
stone-weight-reduction-via-repeated-crushing

## Difficulty  
Easy  

## Description

In a logistics processing facility, heavy stones of varying weights are stored after being collected from multiple sources.

To reduce storage volume and improve handling efficiency, stones are repeatedly processed using a crushing operation. During each operation, the two heaviest stones currently in storage are selected for processing.

If the selected stones have identical weights, both are completely eliminated from storage. If their weights differ, the lighter stone is fully destroyed, while the heavier stone is reduced by an amount equal to the lighter stone's weight. The resulting stone, if any, is returned to storage for potential further processing.

This crushing cycle continues until no more than one stone remains in storage. The final outcome depends entirely on the sequence of weight reductions performed according to these rules.

The objective is to determine the weight of the final remaining stone after all crushing operations have been applied. If all stones are eliminated during processing, the correct result is zero.
## Examples  

### 1  

#### Input  
6  
2 7 4 1 8 1  

#### Output  
1  

### 2  

#### Input  
1  
1  

#### Output  
1  

## Input Format  

- The first line contains an integer n — the number of stones in the warehouse  
- The second line contains n space-separated integers representing the weights of the stones  

## Output Format  

Return a single integer representing the weight of the last remaining stone.  
If no stones remain, return 0.

## Constraints  

1 ≤ n ≤ 30  
1 ≤ stone weight ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

priority-queue.  