# Game-Rule-Handler

## Feature

  Handles the game rules and point scoring criteria
  
## Acceptance Criteria

### Scenario: A player hits the opponent's wall

  Given - An active device with game installed in it and user is signed in
  
  When - A player hits the opponent's wall
  
  Then - trigger the 'play-the-game' module
  
### Scenario: A player hits opponent's paddle

  Given - An active device with game installed in it and user is signed in
  
  When - Opponent stops the pong with his or her paddle
  (paddle moves with certain predefined speed)
  
  Then - ball bounces back with certain predefined speed
