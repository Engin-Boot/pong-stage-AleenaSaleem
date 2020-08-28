# Payment Handler

## Feature

  Handles the payments for buying an incentive
  
## Acceptance Criteria

### Scenario: show payment options to the user

  Given - An active device with game installed in it and user is signed in
  
  When - a user wants to buy and requests payment options
  
  Then - show the list of options and act accordingly
  
### Scenario: payment is successful

  Given - An active device with game installed in it and user is signed in
  
  When - payment is successful
  
  Then - redirect and trigger the paid incentives module
  
### Scenario: payment failed

  Given - An active device with game installed in it and user is signed in
  
  When - payment fails
  
  Then - redirect and prompt if user wants to retry
