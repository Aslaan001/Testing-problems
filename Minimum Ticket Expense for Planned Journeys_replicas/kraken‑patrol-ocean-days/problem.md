## Title
Kraken‑Patrol Ocean Days

## Slug
kraken‑patrol-ocean-days

## Difficulty
Medium

## Description

In this scenario, you are managing kraken‑patrol ocean days. Each required operation occurs on specific days of the year, listed in the array days. To carry out these operations, you must obtain passes that remain valid for consecutive days: a 1‑day, 7‑day, and 30‑day pass. Your objective is to minimize the total cost required to cover all the needed days.

## Examples

### 1

#### Input
6
1 4 6 7 8 20
2 7 15

#### Output
11

#### Explanation
- Buy a 1-day ticket on day 1 for 2 units (covers day 1).
- Buy a 7-day ticket on day 3 for 7 units (covers days 3 to 9, including 4, 6, 7, and 8).
- Buy another 1-day ticket on day 20 for 2 units.
Total expense = 2 + 7 + 2 = 11.

### 2

#### Input
12
1 2 3 4 5 6 7 8 9 10 30 31
2 7 15

#### Output
17

#### Explanation
- Buy a 30-day ticket on day 1 for 15 units (covers days 1 through 30).
- Buy a 1-day ticket on day 31 for 2 units.
Total expense = 17.

## Input Format

- The first line contains an integer n — the number of days you plan to travel.
- The second line contains n space-separated integers representing the travel days.
- The third line contains three integers representing the cost of each ticket type: 1-day, 7-day, and 30-day.

## Output Format

Return a single integer — the minimum possible total cost to cover all travel days.

## Constraints

- 1 ≤ n ≤ 365
- 1 ≤ days[i] ≤ 365
- days is strictly increasing
- costs.length = 3
- 1 ≤ costs[i] ≤ 1000

## Time Limit
1 second

## Memory Limit
256 MB

## Tags
dynamic-programming, cost-optimization, planning, scheduling
