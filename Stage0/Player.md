# Players of the game

## Feature

  This module maintains the existing user, adds or deletes user when prompted
  
## Acceptance Criteria

### Scenario: Game is installed for first time

  Given - An active device with game installed in it
  
  When - The game is newly installed in a device
  
  Then - ask for user details and a user name
  and check if user name is available or not
  
### Scenario: User name already exists

  Given - An active device with game installed in it
  
  When - the entered user name is not available
  
  Then - prompt to enter another username and repeat until a username is available
  
### Scenario: A user name is available

  Given - An active device with game installed in it
  
  When - the entered user name is available
  
  Then - add the user name to list of usernames and trigger the 'start-state' module
  
### Scenario: A player requests to delete account

  Given - An active device with game installed in it and user is signed in
  
  When - there is a request to delete an account
  
  Then - prompt the user to confirm
  
### Scenario: A user confirms account removal

  Given - An active device with game installed in it and user is signed in
  
  When - A user confirms account removal
  
  Then - add the user name to delete_list and sign out
