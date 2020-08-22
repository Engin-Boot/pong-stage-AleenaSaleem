# Theme of the game

## Feature

  Change or display the theme of the game based on eligibility
  
## Acceptance Criteria

### Scenario: apply the theme of the game

  Given - An active device with game installed in it
  
  When - the game board is displayed
  
  Then - Fetch the applicable or chosen theme and apply it
  
### Scenario: Change the theme of the game

  Given - An active device with game installed in it
  
  When - A player chooses to change the theme
  
  Then - fetch the reward points and check if player is eligible to change
  
### Scenario: A player is eligible to change theme

   Given - An active device with game installed in it

   When - A player is eligible to change the theme
   ( has enough reward points )

   Then - Display the theme list and ask to choose one

### Scenario: A player is not eligible to change theme

  Given - An active device with game installed in it
  
  When - A player requests to change theme but is not eligible
  
  Then - Alert the player saying that reward points are not enough
  
### Scenario: Create a theme

  Given - A team of developers working on the game updates
  
  When - A new theme is designed
  
  Then - deploy it , add it to list of themes and update the game
