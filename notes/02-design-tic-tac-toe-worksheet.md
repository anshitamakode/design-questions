# Design Tic-Tac-Toe

## What is Tic-Tac-Toe?

TicTacToe is a 2 player game played on a 3 x 3 board. Each player is allotted a symbol (one X and one O). Initially, the board is empty. Alternatively, each player takes a turn and puts their symbol at any empty slot. The first player to get their symbol over a complete row OR a complete column OR a diagonal wins.

You can play the game within Google Search by just searching for “tictactoe”!

![TicTacToe](https://www.tuitec.com/wp-content/uploads/2016/08/morpion-640x411.jpg)


## Expectations
* The code should be working and functionally correct
* Good software design practices should be followed:
* Code should be modular, readable, extensible
* Separation of concern should be addressed
* Project structured well across multiple files/ packages
* Write unit tests
* No need of GUI


## Requirements gathering

What are some questions you would ask to gather requirements?
```
1. How many number of players should be there in future?
2. What will be the size of the board?
3. What are the different types of player?
4. What will be the winning strategy in game?
```

## Requirements
What will be 10 requirements of the system, according to you?
Do not worry about the correctness of the requirements, just write down whatever comes to your mind.
Your job is not to generate the requirements, but get better at understanding problem statements and anticipating the functionalities your application might need.
```
1. Board of size NXN.
2. Any number of players.
3. Player type can be of Human or Bot.
4. A game can have many player as well as a player can be part of many games.
5. A Bot can has difficulty level(easy, medium, hard).
6. A Human player can have email, name, image.
7. Any player can start the game.
8. Players will play alternatively.
9. Player having consecutive same symbol either in a row, column or diagonally wins the game.
10. If board is full and there is no consecutive same symbol either in a row, column or diagonally, then there will be draw.
```

## Use case diagrams

Are the requirements clear enough to define use cases?
If not, try to think of the actors and their interactions with the system.

### Actors
What would be the actors in this system?
```
1. Human
2. Bot
```

### Use cases

What would be the use cases i.e. the interactions between the actors and the system?

#### Actor 1

Name of the actor - ` Human `

Use cases:
```
1. registerUser()
2. startGame()
3. play()
4. checkWinner()
```
#### Actor 2

Name of the actor - ` Bot `
Use cases:
```
1. setLevel()
2. startGame()
3. play()
4. checkWinner()
```

Add more actors and their use cases as needed.

**Create a use case diagram for the system.**

```

```

## Class diagram

What will be the major classes and their attributes?

```
    Class name
        - Attribute 1
        - Attribute 2
        ...
```

List down the cardinalities of the relationships between the classes.
```
```

Draw the class diagram.
```
```
