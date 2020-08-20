# Handle Exceptions

## Feature

  Handles the external and internals exceptions to game flow
  
## Acceptance Criteria
  
### Scenario: No activity for long (some threshold passed) time
  
  Given - Active devices with game installed in it
  
  When - The game board has been idle for a long time
  
  Then - Either the device sleeps off or
  prompt if the player wants to 'continue' or 'exit'
  
### Scenario: One of the devices shut abruptly

  Given - Active devices with game installed in it
  
  When - One of the devices go powerless
  
  Then - Notify the active player that the other player went offline
  and prompt if the player wants to 'start-over' or 'exit'
  
### Scenario: The game is closed

  Given - Active devices with game installed in it
  
  When - one of the wants to close the game
  
  Then - confirm if player really wants to 'exit' or 'resume'
  
### Scenario: A player confirms exit

  Given - Active devices with game installed in it
  
  When - player confirms game exit
  
  Then - Notify the active player that the other player went offline
  and prompt if the player wants to 'start-over' or 'exit'
