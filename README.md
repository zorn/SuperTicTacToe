# SuperTicTacToe
A game of TicTacToe with a twist - personal learning project for iOS

This is a personal development project/portfolio project I am currently working on to develop my Swift capabilities

Please keep in mind while looking at the project that it is still a work in progress, the app is currently at what I would consider to be a Alpha state (maybe). The User Interface is serviceable for what the app is, but was not the focus of the project, so apologize if its not the prettiest app you've ever seen.

Currently on the to-do list as I have time:

1) music and sound effects
2) add in camera support for player profiles (currently all profiles get a generic placeholder image).
3) UI overhaul.


Synopsis:
This project is an extension of a final project I originally wrote in Java for school. There is a standard mode for a 
plain vanilla game of TicTacToe and a super mode. In super mode each player has access to a super power
which they can use once per game.

The super powers are:

Freeze - Player can freeze one tile for a turn. It will unfreeze at the beginning of that players next turn.

Swap - Player can choose one of their tiles and it will randomly be swapped with one of their opponents tiles.

Rewind - When activated Rewind undoes both players last moves, effectively stepping the game back a turn.

![Main Menu](App%20Screen%20Shots/Main%20Menu%20Screen.png)
![Player Select Screen](App%20Screen%20Shots/PlayerSelectScreen.png)
![Standard Game Mode](App%20Screen%20Shots/StandardModeScreen.png)
![Super Game Mode](App%20Screen%20Shots/SuperModeScreen.png)

The app also has the ability to create player profiles (hit the + button in the top right of the Player Profiles screen to create a new profile), which will track win/loss stats and allow the player
to select which power they want to use. There are currently 5 generic profiles permanently embedded, one for each of the
super powers as well as generic Player1/Player2 profiles, which when selected will randomly select one of the powers at the start
each game.

![Player Profile Table Screen](App%20Screen%20Shots/PlayerProfileTableScreen.png)
![Create New Player Profile Screen](App%20Screen%20Shots/CreateNewPlayerScreen.png)
![Play Profile Detail View](App%20Screen%20Shots/ProfileDetailViewScreen.png)

