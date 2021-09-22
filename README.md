# Bagels

In Bagels, a deductive logic game, you must guess a secret three-digit number
based on clues. The game offers one of the following hints in response to your guess:
“Pico” when your guess has a correct digit in the wrong place, “Fermi” when your guess has a correct
digit in the correct place, and “Bagels” if your guess has no correct digits. You have 10 tries to guess the
secret number.

TODO:
- Make the NUM_DIGITS configurable
- make MAX_GUESSES configurable
- NUM_DIGITS must be less than 10


When you run bagels.ts, the output will look like this:
```shell
Bagels, a deductive logic game.

I am thinking of a 3-digit number. Try to guess what it is.
Here are some clues:
When I say: That means:
 Pico One digit is correct but in the wrong position.
 Fermi One digit is correct and in the right position.
 Bagels No digit is correct.
I have thought up a number.
 You have 10 guesses to get it.
Guess #1:
> 123
Pico
Guess #2:
> 456
Bagels
Guess #3:
> 178
Pico Pico
--snip--
Guess #7:
> 791
Fermi Fermi
Guess #8:
> 701
You got it!
Do you want to play again? (yes or no)
> no
Thanks for playing!
```