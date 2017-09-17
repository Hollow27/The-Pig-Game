# The Pig Dice Game

Each turn, a player repeatedly rolls a die until either a 1 is rolled or the player decides to "hold":

If the player rolls a 1, they score nothing and it becomes the next player's turn.
If the player rolls any other number, it is added to their turn total and the player's turn continues.
If a player chooses to "hold", their turn total is added to their score, and it becomes the next player's turn.
The first player to score 100 or more points wins.

For example, the first player, Ann, begins a turn with a roll of 5. Ann could hold and score 5 points, but chooses to roll again. Ann rolls a 2, and could hold with a turn total of 7 points, but chooses to roll again. Ann rolls a 1, and must end her turn without scoring. The next player, Bob, rolls the sequence 4-5-3-5-5, after which he chooses to hold, and adds his turn total of 22 points to his score.

# Specifications

1. The game begins when the Player rolls, return a random number between '1' and '6'.

2. If current Player rolls '2', they go again. * Example Input: Click/Press "Roll" * Example Output: A 2 is rolled, so the current Player is prompted to roll again. 2b. If current Player rolls '1', they score nothing, and their turn is over. * Example Input: Rolls '1' * Example Output: Current Player's score for that turn is 0, and it becomes the other Player's turn.

3. If current Player rolls a number between '2' and '6', Player has the option to 'hold' or 'roll' again.

Example Input: Rolls '2'
Example Output: Current Player's score for that turn is 2, and they can either hold or roll again.

4. The first player to hit greater than or equal to 100 points wins.

Example Input: The number of points a user has added to their Total Score reaches 100 or greater.
Example Output: "Looks like we have a winner!"

# Setup/Installation Requirements

Clone this repository
If editing, open project directory in Code Editor of choice
If viewing, open index.html in a web browser

# Known Bugs

No known bugs.

# Support and contact details

For comments or questions, please email zohaibshahzad.to@gmail.com

# Technologies Used

HTML5, CSS3, ES5 JavaScript (Vanilla)

Copyright (c) 2017 <b>Zohaib Shahzad</b>
