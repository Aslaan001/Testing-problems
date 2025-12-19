## Title
Cluster Link Optimization

## Slug
cluster-link-optimization

## Difficulty
Hard

## Description
In modern infrastructure engineering, cluster link optimization is a critical problem faced when designing reliable and cost-efficient distributed systems.

An organization operates a sequence of servers, each configured with a specific protocol identifier.
Initially, these servers function independently with no communication paths between them.

To enable full system functionality, connections must be established so that every server can communicate with all others, either directly or indirectly.
Each potential connection spans a contiguous range of servers, and its cost is derived from the greatest common divisor of the protocol identifiers within that range.

The challenge is to select a set of connections that guarantees complete connectivity of the server sequence while minimizing the total accumulated connection cost.
Every chosen connection contributes its computed cost, and all servers must ultimately belong to a single connected network.


## Examples

### 1
#### Input
3  
4 2 6  

#### Output
4  

#### Explanation
One optimal strategy is to connect the servers in a way that ensures full connectivity while minimizing the sum of gcd-based connection costs.

### 2
#### Input
6  
2 4 6 7 14 21  

#### Output
5  

#### Explanation
It is possible to connect all servers using connections whose costs are small (for example, cost 1), achieving full connectivity with a total cost of 5.

## Input Format
- The first line contains a single integer n — the number of servers.
- The second line contains n positive integers p1, p2, …, pn, where pi denotes the protocol type of the i-th server.

## Output Format
Return a single integer — the minimum total cost required to connect all servers so that every server can reach every other server.

## Constraints
- 2 ≤ n ≤ 2 × 10^5  
- 1 ≤ pi ≤ 10^9  

## Time Limit
1 second

## Memory Limit
256 megabytes

## Tags
maths, hackwithinfy

## Company
infosys
