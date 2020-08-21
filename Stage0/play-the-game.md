# Playing the game

## Feature

Maintains scores and time for game rounds

## Acceptance Criteria

### Scenario: A player scores a point

  Given - Devices with the game installed in them

  When - Any player scores a point and there is time left

  Then - Update the scores and check if maximum points are scored

### Scenario: Maximum points are reached

  Given - Devices with the game installed in them
  
  When - any player scores maximum points
  
  Then - Declare the winner and prompt for 'another-round or 'go-back'
  
### Scenario: The timer times out

  Given - Devices with the game installed in them
  
  When - The round is timed out
  
  Then - Declare a winner or tie depending on the score and
  prompt for 'another-round' or 'go-back'
