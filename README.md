# Guessing Game

This project is to wet your feet in the RUST programming language...

## How it works

1) The program will generate a random integer between 1 and 100.

2) It will then prompt the player to enter a guess.

3) After a guess is entered, the program will indicate whether the guess is too low or too high.

4) If the guess is correct, the game will print a congratulatory message and exit.

## Variables

```Rust
let mut guess = String::new();
```

- ```let``` statement creates the variable with the given value.

- By default variables are immutable.

- To make a variable mutable, we add ```mut``` before the variable name.

```Rust
let apples = 5; // immutable
let mut bananas = 5; // mutable
```

The ```::``` syntax in the ```::``` new line indicates that new is an associated function of the String type. An associated function is a function that’s implemented on a type, in this case String. This new function creates a new, empty string.
