## Title

Binary Encoding Load Governance

## Slug

binary-encoding-load-governance

## Difficulty

Medium

## Description

A multinational semiconductor manufacturer operates large production batches of programmable
processing units.  Each unit stores a fixed-width binary value, and the factory provisions exactly
one unit for every integer from 1 to (2^p − 1), ensuring uniform coverage of operational states.  To
reduce aggregate power draw without altering functional coverage, engineers are allowed to exchange
individual bits at matching positions between any two units.  This low-level operation preserves
total information while allowing redistribution of binary weight across the fleet.  The manufacturer
evaluates energy efficiency using a system-wide metric defined as the product of all unit values.
Configurations resulting in any unit evaluating to zero violate hardware safety guarantees and are
rejected.  Determine the minimum achievable non-zero system product after applying any number of
valid bit exchange operations.  Because production-scale numbers are extremely large, the final
value must be reported modulo 10^9 + 7, with optimization performed prior to modular reduction.
Such optimizations are common in large-scale silicon validation environments.

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
