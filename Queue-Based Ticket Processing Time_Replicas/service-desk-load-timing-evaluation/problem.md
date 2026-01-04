## Title
Service Desk Load Timing Evaluation

## Slug
service-desk-load-timing-evaluation

## Difficulty
Medium

## Description

Large service organizations often rely on a single-point service counter to process customer requests in a strictly ordered queue. Each customer arrives with a predefined service requirement that must be fulfilled sequentially, without parallel processing.

In this scenario, customers wait in a first-in-first-out queue to purchase service tickets. Each ticket transaction takes exactly one unit of time, and customers are only permitted to complete one transaction at a time.

After completing a transaction, a customer who still requires additional tickets is placed back at the end of the queue, ensuring fairness and strict order preservation. Customers who complete all their required purchases immediately exit the system and no longer affect queue dynamics.

From an operational analytics perspective, it is important to predict how long a specific customer will remain in the system. Given the initial queue configuration and the position of a target customer, your task is to compute the total time required for that customer to finish all ticket purchases under the defined queue-processing rules.

## Examples  

### 1  

#### Input  
3  
2 3 2  
2  

#### Output  
6  

#### Explanation  

The initial queue is [2, 3, 2], and the target customer is at index 2.

At each second, the front customer buys one ticket and either moves to the back or leaves the queue.

After 6 seconds, the customer who started at position 2 finishes purchasing all tickets.

### 2  

#### Input  
4  
5 1 1 1  
0  

#### Output  
8  

#### Explanation  

The initial queue is [5, 1, 1, 1], and the target customer is at index 0.

Other customers finish earlier and leave the queue, while the target customer continues buying tickets.

After 8 seconds, the customer at position 0 completes their purchases.

## Input Format  

- The first line contains an integer n — the number of customers in the queue.  
- The second line contains n space-separated integers representing the number of tickets each customer wants to buy.  
- The third line contains an integer k — the index of the target customer.  

## Output Format  

Return a single integer — the total time taken for the target customer to finish buying tickets.

## Constraints  

1 ≤ n ≤ 1000  
1 ≤ tickets[i] ≤ 1000  
0 ≤ k < n  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue, array  
