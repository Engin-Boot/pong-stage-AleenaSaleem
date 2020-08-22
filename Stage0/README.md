# The Essentials

* The stage 0 of pong game captures the basics of it

* Those basics include different modules as described below:

  * Start-state: This module captures all the scenarios that can occur
  when the game is opened

  * Get-the-second-player: This module decides whether the game is going to be
  single player or double player type based on player choice
  
  * Play-the-game: This one ensures that all the in-game scenarios
  during an active game are handled

  * Game-rule-handler: This states when a point is scored according to rules

  * Exceptions: This modules captures all the external and internal
  exceptions during a game

* The interaction among modules has been illustrated in **sequence start** file

* The modules in **Design** folder handle the display of the pong , paddle
and the theme of the game and only interact with the modules outside when
game board needs to be displayed.
