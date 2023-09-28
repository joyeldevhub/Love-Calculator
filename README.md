# Love-Calculator
Using Javascript Code.

## Explanation
The code you provided seems to be a simple love calculator that takes the names of two individuals, calculates a "love score" based on a random number generator, and then displays the result to the user using JavaScript's prompt and alert functions.

Here's an explanation of how the code works:

The code starts by using the prompt function twice to get input from the user. It prompts the user to enter their name and then the name of the person they are interested in.

After obtaining the names, it generates a random love score using Math.random(). Math.random() returns a random floating-point number between 0 (inclusive) and 1 (exclusive).

It multiplies the random number by 100 to get a value between 0 and 99.9999999 (inclusive).

It then uses Math.floor() to round down this random number to the nearest integer. This ensures that the love score is a whole number between 0 and 100.

The code adds 1 to the love score to make it inclusive of 100. So, the final love score is between 1 and 100.

Finally, it displays the love score to the user using the alert function along with a message. The love score is concatenated with the string "Your Love Score is" before being displayed.
