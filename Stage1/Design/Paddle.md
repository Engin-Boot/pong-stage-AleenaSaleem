# Paddle properties

## Feature

  define the properties of paddle such as size , speed and Color
  
## Acceptance Criteria

### Scenario: change the paddle properties - update

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
  
  Then - alert that reward points are not sufficient
