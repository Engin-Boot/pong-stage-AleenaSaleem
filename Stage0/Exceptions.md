# Handle Exceptions

## Feature

  Handles the external and internals exceptions to game flow
  
## Acceptance Criteria
  
### Scenario: No activity for long (some threshold) time
  
  Given - Active device with game installed in it
  
  When - The game board has been idle for a long time
  
  Then - Either the device sleeps off or
  prompt if the player wants to 'continue' or 'exit'
  
### Scenario: The device shuts abruptly

  Given - Active device with game installed in it
  
  When - the device shuts down during an active game
  
  Then - On reopening the game, trigger the 'start-state' module
  
### Scenario: The game is closed

  Given - Active device with game installed in it
  
  When - A player wants to close the game
  
  Then - confirm if player really wants to 'exit' or 'resume'
  
### Scenario: A player confirms exit

  Given - Active device with game installed in it
  
  When - player confirms game exit
  
  Then - log the statistics and exit
