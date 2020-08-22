# Playing the game

## Feature

Maintains scores and time for game rounds

## Acceptance Criteria

### Scenario: A player scores a point

  Given - An active device with the game installed in it

  When - Any player scores a point and there is time left

  Then - Update the scores depending on the game type
  and check if maximum points are scored

### Scenario: Maximum points are reached

  Given - An active device with the game installed in it
  
  When - any player scores maximum points
  
  Then - Declare the winner or high score depending on the game type
  and prompt for 'another-round or 'go-back'
  
### Scenario: The timer times out in either single or double player

  Given - An active device with the game installed in it
  
  When - The round is timed out
  
  Then - Declare a winner or high score or tie depending on the score and game type
  and prompt for 'another-round' or 'go-back'
  
### Scenario: Calculate reward points

  Given - An active device with the game installed in it
  
  When - A player scores five points consecutively
  
  Then - Add a point to reward points
