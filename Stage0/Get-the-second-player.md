# Add a second player

## Feature

  On being triggered by 'start-game' button, adds a second player for game to start
  
## Acceptance criteria

### Scenario: Second player is available

  Given - An active device with game installed in it and user is signed in
  and 'add-player' or 'play-single' button is displayed
 
  When - First player clicks on 'add-player'
  
  Then - show text box to get the second player's name and
  trigger 'play-the-game' module
  
### Scenario: second player is not available

  Given - An active device with game installed in it and user is signed in
  
  When - A player chooses to 'play-single'
  
  Then -  Single player plays both the sides and
  trigger 'play-the-game' module
