Bowling task
=============

Programming challenge for counting the score in a bowling game

<h3>Task</h3>

Your task is to sum up and output one player's score in a game of 10-pin bowling after a game of up to 21 rolls.

<h3>Scoring</h3>

After each round the number of pins knocked down in that round is counted into the final score. If a player knocks down all ten pins in the first roll of a round, this is a strike, and the round is over. Otherwise, the round lasts for one more roll. If the second roll of a round knocks down all the remaining pins, this is a spare.

For each strike there is a bonus equal to the sum of pins knocked down in the two next rolls. For each spare there is a bonus equal to the numer of pins knocked down in the next roll.

The 10th and final round, the player may be granted extra rolls: In case of a strike, the player gets two more rolls to make up his strike bonus. In case of a spare, the player gets one more roll.

<h3>Input</h3>

Your input will consist of a text file defining a (valid) game of bowling.<br>
The rolls are represented as a sequence of integers. Each integer corresponds to the number of pins that were knocked down in that roll.
See `sample1.in` that should return the score `131`, and `sample2.in` that should return `183`.

<h3>Output</h3>

Your output should be the total score of the game. Just print to stdout.

<h3>Hand-in</h3>

* Source code (prerably Python or JavaScript)
* Some tests showing that it works
* Short assessment of the code quality, what could be better
