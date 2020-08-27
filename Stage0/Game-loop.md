# The Game loop

## Feature
  
  A game loop runs continuously during game play.  
  Each turn of the loop, it processes user input without blocking,
  updates the game state, and renders the game.
  
## Acceptance criteria

## Process Input

### Scenario: Take the current frame screenshot

  Given - An active device with game installed in it and user is signed in
  
  When - There is new frame input and game is not paused
  
  Then - call the 'update' method followed by 'render' method

## Update the scene

### Scenario: Input calls the update method

  Given - An active device with game installed in it and user is signed in
  
  When - 'Update' method is called
  
  Then - Update the pong and paddle and check for collisions
  
### Scenario: Collision between pong and paddle

  Given - An active device with game installed in it and user is signed in
  
  When - there is collision between pong and paddle
  
  Then - Bounce back the pong
  
### Scenario: Collision between pong and top or bottom of screen

  Given - An active device with game installed in it and user is signed in
  
  When - there is collision between pong and top or bottom of the screen
  
  Then - Bounce back the pong 
  
### Scenario: Collision between pong and right or left wall

  Given - An active device with game installed in it and user is signed in
  
  When - there is collision between pong and right or left wall
  
  Then - Bounce back the pong and trigger the 'play-the-game' module for score updation
  
## Render new frame

### Scenario: frame has been updated successfully

  Given - An active device with game installed in it and user is signed in
  
  When - Frame is ready to be drawm
  
  Then - draw the new frame on the scene and repeat the game loop
