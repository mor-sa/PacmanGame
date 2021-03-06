# Pacman Game
Pacman game by Ben Margalit and Mor Saranga

This Repository Website URL: https://mor-sa.github.io/PacmanGame/

Class Submission Website URL: https://web-development-environments-2021.github.io/Assignment2_211896535_205543606/

### Overview

This game is pacman simple game for our web development course. We used Javascript, Jquery, HTML and CSS.
The game is built according to the instruction given by course staff.

![image](https://user-images.githubusercontent.com/62620992/116438440-1dc4f400-a857-11eb-8e09-8bffa354eeb7.png)

## What's in the site?
* **Home** - a page that contains a logo, Legister and Login buttons.
* **Register** - a page that allows the user to register to the site, using jquery validation to make sure the inputs are valid.
* **Login** - a page that allows the user to login, using jquery validation to make sure the inputs are valid.
* **Settings** - a page that asks the user to select preferences for the game, such as keys to play, number of food balls, number of ghosts, time of the game, colors for the food points. There is a random button that randomly changes the prefernces.
* **Game** - a page that has the game itself and at the top of the game it shows: the username, score, time passed from the game's beginning, and how many lives the user has. On the side, the user sees the preferences he has chosen and a new game button.

![image](https://user-images.githubusercontent.com/62620992/116438895-9a57d280-a857-11eb-9abe-9df7ef406c37.png)

## Game Rules:
* Use the keys selected to move around the board.
* Eat food for score. There are 3 kinds of food points, smaller worth 5 points, medium worth 15 points and big worth 25 points.
* If a ghost catches the pacman, you lose 1 life and 10 points off the score.
* If you eat the special moving candy, you get 50 points.

![image](https://user-images.githubusercontent.com/62620992/116438671-5795fa80-a857-11eb-92d9-ec9f0367ae09.png)
* Game ends when:
    * Win: if pacman eats all the food on the board or time's up and the score is above 100 points.
    * Lose: if pacman loses all it's life (Loser) or time's up and the score is below 100 poins (You can do better...)

## Special Functionality
We've added the following special functionality:
* **Teleport** - at the center of the board there is a teleport cell. If pacman or one of the ghosts or the candy walks into it, they get thrown into a random position in the board.

![image](https://user-images.githubusercontent.com/62620992/116438539-37663b80-a857-11eb-8362-b6fe6720834e.png)
* **Move to other side of the board** - There are holes in the walls sides, if pacman goes into it and walks past it, it comes out of the oopposite side of the board. The ghosts and candy can't go through it.
