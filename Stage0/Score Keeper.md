# Score-Keeper

## Feature

This module takes care of scores in the game
and declare winner

## Acceptance Criteria

### Scenario: Register point for players

Given : Game is ON

When : Collision module notify to update score of certain player

Then : Update score by one for that certain player

### Scenario: Declare Winner

Given : Game is ON

When : Any player gets 10th point

Then : Trigger winner screen with player name in argument
in Play-Paise-Start module