# Collision

## Feature

This module governs what happens in case of collision
between any two objects

## Acceptance Criteria

### Scenario: Collision of Ball and paddle

- Given : Game is ON.

- When : Ball and Paddle Collide

- Then : Change x-axis component of velocity in movement module
if ball collide with 'vertical' paddles.
Update acceleration in movement module
based on ball and paddle property modules.

### Scenario: Collision of Ball and wall

- Given : Game is ON.

- When : Ball and wall Collide

- Then : Update score of opposite player in score-keeper module 
and position ball at the centre,
If ball collide with 'vertical' walls
**OR**
change y-axis component of velocity in movement module
if ball collide with 'horizontal' walls.
Update acceleration in movement module
based on ball and paddle property modules.
