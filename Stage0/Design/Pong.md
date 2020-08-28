# Pong properties

## Feature

  define the properties of pong such as Size , Speed , direction and Color
  
## Acceptance Criteria

### Scenario: Display the pong on game board

  Given - An active device with game installed in it and user is signed in
  
  When - The game board is displayed
  
  Then - set the pong properties and display it
  
### Scenario: change the pong properties - update

  Given - An active device with game installed in it and user is signed in
  
  When - A player requests change in any of the properties
  
  Then - Fetch the reward points and check if player is eligible to change
  
### Scenario: A player is eligible to change

  Given - An active device with game installed in it and user is signed in
  
  When - A player requests and is eligible to change properties

  Then - ask to choose property and specify the options
  and update property accordingly
  
### Scenario: A player is not eligible to change properties

  Given - An active device with game installed in it and user is signed in
  
  When - A player is not eligible to change
  
  Then - Alert that reward points are not sufficient
  
### Scenario: Change in direction of the pong - reverse direction

  Given - An active device with game installed in it and user is signed in
  
  When - pong hits either the wall or the paddle
  
  Then - change the pong direction
