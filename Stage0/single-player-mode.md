# Single-Player

## Feature

Single player feature (vs CPU)

## Acceptance Criteria

### Scenario: Select Player 1 Name

  Given the application is running

  When I select Single Player(vs CPU) in the menu

  Then display a text box and change the name to entered name

### Scenario: Choose Difficulty Setting

  Given the application is running

  When I select Single Player(vs CPU) in the menu
  and then selects the name

  Then display three difficulty level(Easy, Medium, Hard)

### Scenario: User Winning

  Given the game is started

  When the user score 10 points first

  Then declare the user as winner
  and record it in the stats(last 10 games)
  and update win ratio

### Scenario: CPU Winning

  Given the game is started

  When the CPU score 10 points first

  Then declare the CPU as winner
  and record it in the stats(last 10 games)
  and update win ratio

### Scenario: Prompt Restart Match

  Given the game is started

  When either Player 1 or CPU wins the game

  Then ask the user about restarting the game.

### Scenario: Restart Match

  Given the game is over

  When User select restart match

  Then restart the match.
