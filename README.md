# Bulls-CowsGame
Java class that implements the classic 'Bulls &amp; Cows' word game using 4 digit numbers

Rules:

The class will generate a random 4 digit number, that has no zeroes in it anywhere, and no repeating digits.

You have to guess that number within 20 attempts.

There are two counts: Bulls and Cows-

Bulls are the total number of digits in your guess that have the correct value and the correct place, and
Cows are the total number of digits in your guess that are in the mystery number but in the wrong place.

For eg.

Generated : 5721
You guessed: 3795

Here 7 is a Bull (right value in the correct (hundreds) place) and 5 is a Cow (you guessed a correct digit but didn't get the place right)

For each guess you make, your input (using Scanner.in) will be validated and the Bulls and Cows will be returned to you.

You win if you get all 4 bulls before the attempts run out.
