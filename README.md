# CIS166A Final Project - Memory Game Project
by [Saira Qureshi]

## What is the Memory Game
This is a simple game built to test a users memory. There's a deck of cards with different icons.
![snippet](img/snippet.png)

## Challenge
Match cards in less time with less moves.

## How to Play
The main Objective is to match most card pairs
If two cards selected are identical a match is made and are made visible on the screen else if the two cards selected are not identical a miss is made and the cards are then hidden
a counter is set to record every move made to either get a match or a miss and a timmer is set to check how long is spent spent on the game.
If all card pairs are successfully matched it displays a congratulation message, with number of moves, how long it took to complete and a replay button if you wish to replay

## How I built the Memory Game

1. First I did was to declare an array variable which holds all the card image pairs
2. I created a variable to hold a value for the number of moves
3. I created a counter variable that would hold the move element using query selector
4. I created an empty array to store the openedcards and also a variable to store the minutes and seconds value for the timer
5. I did a reset to the game and made an append for each card in the array
6. I used the append to match opencards to see if it gives a match or an unmatch and a counter was set to determine number of moves made
7. Then a function to display congratulation message and play again was implemented
