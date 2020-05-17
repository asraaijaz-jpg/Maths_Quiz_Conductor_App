# Math Trainer
This is an extremely basic math game using vanilla JavaScript.

## Notes
This app shows a random math equation to users by calculating two random integers in the range (0, 100) and assigning it one of the four basic operators:
1. Addition
2. Subtraction
3. Multiplication
4. Division

Answers that result in in a float are rounded to two decimal places using the `toFixed()` function.

If a user answers the question correctly, the background turns green for 1000 ms and then turns back to grey and generates a new question. if a user answers the question incorrectly, the background turns red for 1000 ms and then burns back to grey.

Users can use buttons to generate a new question or to see the answer.

Hosted at [Math Trainer](christian-cleberg.gitlab.io/math-trainer).
