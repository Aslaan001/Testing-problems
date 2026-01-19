## Title

Chip State Energy Minimization

## Slug

chip-state-energy-minimization

## Difficulty

Medium

## Description

A financial trading firm deploys FPGA-based accelerators where internal state registers encode
binary values representing configuration states.  For a given bit-width p, the deployment includes
registers corresponding to all integers from 1 to (2^p − 1).  To minimize aggregate signal
amplification cost, the firm permits controlled bit exchanges between registers at identical
positions.  These exchanges do not change the set of available states but allow redistribution of
high-weight bits.  The platform defines total amplification cost as the product of all register
values.  States that introduce zero-valued registers invalidate transaction guarantees and are
disallowed.  Compute the minimum achievable non-zero amplification cost after any sequence of valid
bit swaps, reporting the answer modulo 10^9 + 7.  This scenario reflects real-world constraints in
hardware optimization pipelines.  Such optimizations are common in large-scale silicon validation
environments.

## Examples

### 1

#### Input

p = 1

#### Output

1

#### Explanation

Only one chip exists with value 1.
No rebalancing is possible, so the product remains 1.

### 2

#### Input

p = 2

#### Output

6

#### Explanation

The chips represent the values:

1, 2, 3

Any rebalancing either keeps the product unchanged or produces a zero value.
Thus, the minimum non-zero product is:

1 × 2 × 3 = 6

### 3

#### Input

p = 3

#### Output

1512

#### Explanation

The chips initially represent:

1, 2, 3, 4, 5, 6, 7

By swapping bits strategically, the chips can be rearranged to:

1, 6, 1, 6, 1, 6, 7

The resulting product is:

1 × 6 × 1 × 6 × 1 × 6 × 7 = 1512

This is the minimum non-zero product achievable.

## Input Format

- A single integer p representing the number of bits used in each chip

## Output Format

- Return a single integer representing the minimum non-zero product modulo 10^9 + 7

## Constraints

1 <= p <= 60

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

recursion
