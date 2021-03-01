# Guessing Game

This is a simple game that work on CLI.

It has been created by following [The Rust Programming Languate](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html) webpage.

## Installation

Just clone it.

```
$ git clone https://github.com/nsbt/guessing_game.git
$ cd guessing_game
```

## How to play

The program will generate a random integer between 1 and 100.
It will then prompt the player to enter a guess.
After a guess is entered, the program will indicate whether the guess is too low or too high.
If the guess is correct, the game will print a congratulatory message and exit.

```
$ cargo run
Guess the number!
Please input your guess.
50
You guessed: 50
Too small!
Please input your guess.
75
You guessed: 75
Too big!
Please input your guess.
70
You guessed: 70
Too small!
Please input your guess.
72
You guessed: 72
You win!
```
