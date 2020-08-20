# Starting or Resuming a game

## Feature

Starts a new game or resumes a pending one based on user choice

## Acceptance Criteria

### Scenario: Player opens the game with an existing pending game

  Given - An active device with game installed in it

  When - User opens the game and finds an old pending game

  Then - Prompt the user to choose between 'start-over' and 'resume'

### Scenario: Player chooses to start a new game or there is no existing game

  Given - An active device with game installed in it
  
  When - User opens the game
  
  Then - Display the game board with initial statistics and 'start-game' button
  
### Scenario: Player chooses to resume an old game

  Given - An active device with game installed in it
  
  When - User taps on 'resume'
  
  Then - Display the game board with logged statistics and 'start-game' button
  
### Scenario: User clicks on 'start-game' button

  Given - An active device with game installed in it
  
  When - User clicks on 'start-game'  button
  
  Then - start the game and trigger the keep-score module
