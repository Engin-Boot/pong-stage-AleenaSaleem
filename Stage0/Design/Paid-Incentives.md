# Paid Incentives or features in the game

## Feature

* This module handles the payment for buying a feature.

* Buying a feature implies buying reward points basically.
  
* Any changes can be made if there are sufficient reward points.
  
* A reward point is gifted if a player scores five points consecutively.
  
* Minimum 50 reward points are needed to change any feature.

* Reward points , both bought and earned , expire after 5 days of life time.

## Acceptance criteria

### Scenario: Show user history of incentives bought

  Given - An active device with game installed in it and user is signed in
  
  When - User requests to see incentives history
  
  Then - show the list
  
### Scenario: Provide an incentive

  Given - An active device with game installed in it and user is signed in
  
  When - User wants to buy an incentive
  
  Then - show the list of options and trigger the payment handler module
  
### Scenario: Payment is successful

  Given - An active device with game installed in it and user is signed in
  
  When - The payment for an incentive is successful
  
  Then - Update the history and trigger the necessary modules to make changes
