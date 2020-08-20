# Add a second player

## Feature

  On being triggered by 'start-game' button, adds a second player for game to start
  
## Acceptance criteria

### Scenario: First player invites another player

  Given - An active device with game installed in it and 'add-player' button is displayed
  
  When - First player clicks on 'invite-player'
  
  Then - show list of players to choose from
  
### Scenario: second player is chosen

  Given - An active device with game installed in it
  
  When - A player chooses another player to invite
  
  Then -  notify the second player to either 'accept' or 'decline'
  
### Scenario: Second player accepts

  Given: An active device with game installed in it
  
  When - second player accepts the invite
  
  Then - start the game and trigger the 'play-the-game' module
  
### Scenario: Second player declines

  Given - An active device with game installed in it
  
  When - Second player declines the invite
  
  Then - notify the first player and prompt to 'choose-another-player' or 'exit'
