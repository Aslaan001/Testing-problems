## Title
The Serpent Canyon's Gliding Stonehead

## Slug
the-serpent-canyons-gliding-stonehead

## Difficulty
Hard

## Description
In this scenario, the serpent canyon's gliding stonehead, creating a dangerous horizontal obstacle that shifts over time. A convex polygon represents this moving threat, sliding left at constant speed. Meanwhile, the protagonist ascends vertically with limited speed along a fixed line, attempting to reach the top safely without ever intersecting the moving shape. Despite the thematic change, the geometric and movement mechanics remain identical to the original problem.

## Examples

### 1
#### Input

5 5 1 2
1 2
3 1
4 3
3 4
1 4

#### Output
5.0000000000


## Input Format
A line containing integers n, w, v, u  
Then n lines, each containing coordinates xi yi of polygon vertices in CCW order

n is the number of polygon vertices  
w is the road width  
v is the bus speed  
u is the pedestrian's maximum vertical speed

## Output Format
Return the minimum time needed to reach (0, w) safely.

## Constraints
3 ≤ n ≤ 10⁴  
1 ≤ w ≤ 10⁹  
1 ≤ v, u ≤ 1000  
−10⁹ ≤ xi ≤ 10⁹  
0 ≤ yi ≤ w  
Polygon is convex and non-degenerate

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
geometry,hackwithinfy.

## Company
infosys
