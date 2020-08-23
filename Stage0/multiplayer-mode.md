# Multiplayer
## Feature

Multiplayer Feature (Player 1 vs Player 2)

## Acceptance Criteria

### Scenario: Select Player Name

  Given the application is running

  When I select Multiplayer in the menu

  Then prompt for player 1 name first
  and then prompt for player 2 name
  and update the names of both player

### Scenario: Player 1 Winning

  Given the game is started

  When the Player 1 score 10 points first

  Then declare the Player 1 as winner
  and record it in the stats(last 10 games) in multiplayer section
  and update the win ratio

### Scenario: Player 2 Winning

  Given the game is started

  When the Player 2 score 10 points first

  Then declare the Player 2 as winner
  and record it in the stats(last 10 games) in multiplayer section
  and update the win ratio.

### Scenario: Prompt Restart Match

  Given the game is started

  When either Player 1 or Player 2 wins the game

  Then ask the user about restarting the game.

### Scenario: Restart Match

  Given the game is over

  When User select restart match

  Then restart the match.
