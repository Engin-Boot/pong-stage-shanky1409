# Interaction Sequences

## Startup Sequence

sequenceDiagram

	Menu->>+Single Player: To start single player game
    Menu->>+MultiPlayer: To start Multiplayer game
    Menu->>+Stats: To check player stats
    Menu->>+Setting: To change background setting, ball color
    Menu->>+Exit: To exit the game 	

## Movement Initiation

### For Single Player Mode

    On press of any key, game will start with ball movement towards the user

### For MultiPlayer Mode

    On press of any key, game will start with ball movement towards random user

## One score

    When the ball touch left/right wall missing the paddle, one point is scored
