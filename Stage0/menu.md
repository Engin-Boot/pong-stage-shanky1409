# Menu

## Feature

### Menu Page open when the program is started

## Acceptance Criteria

### Scenario: Selecting Single Player Mode

  Given the Ping-Pong application is running

  When I select Single Player mode in the menu

  Then open the screen asking Player 1 name.

### Scenario: Selecting Multi Player Mode

  Given the Ping-Pong application is running

  When I select Multi Player mode in the menu

  Then open the screen asking Player 1 and Player 2 name.

### Scenario: Selecting Stats option in menu

  Given the Ping-Pong application is running

  When I select Stats option in the menu

  Then open the screen displaying players last 10 match stats grouped as
  difficulty.

### Scenario: Selecting Setting option in menu

  Given the Ping-Pong application is running

  When I select Setting option in the menu

  Then open the screen where I can select Game sound, Background theme,
  Ball theme.

### Scenario: Selecting Exit match

  Given the Ping-Pong application is running

  When I select Exit option in the menu

  Then close the application.
