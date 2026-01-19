## Title

Chip-Level Load Compression

## Slug

chip-level-load-compression

## Difficulty

Medium

## Description

A cloud hardware provider maintains a dense pool of binary-encoded compute registers used for
latency-sensitive workloads.  At initialization, the pool contains registers representing every
positive integer up to (2^p − 1), encoded using exactly p bits.  To rebalance thermal stress across
racks, operators may swap bits at the same index between any two registers.  These operations can be
performed repeatedly and independently without restriction.  The operational cost of the pool is
quantified as the multiplicative combination of all register values.  Any configuration producing a
zero-valued register is considered invalid due to fault propagation risk.  Your task is to compute
the lowest possible non-zero cost attainable through allowed rebalancing actions, returning the
result modulo 10^9 + 7.  This scenario reflects real-world constraints in hardware optimization
pipelines.

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
