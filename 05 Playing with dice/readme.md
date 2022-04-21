# Episode 5: Playing with dice

* Link to video: (not yet recorded)
* Link to presentation: (not yet created)
* Link to spreadsheet: (not yet created)

## (only sketches so far)

* In this episode we will look at how to use a spreadsheet to do Monte Carlo simulations of something a bit more complex. We will imagine a game where you move on a board by rolling five dice, and the number of steps is decided by how many equal results the dice show. A triplet means three steps, a pair (or two) means two steps, and five singlets means one step. We will use spreadsheet math to find the probabilities for moving 1 to 5 steps, and look at what what the probability distribution can tell us about a game using such mechanisms.

* Spreadsheet: Rolling five dice, finding the most common result, and finding how many dice show that result. Getting the probability distribution.

* Some words on what the results mean: The typical result is a pair, which happens about seven out of ten times. About one in ten rolls give a single step, two in ten give three steps. Four and especially five steps are outliers, which means that they should give cheers around the table. On average you get to move around 2.14 steps.
* If this wasn't a game where you get to move 1–5 steps, but get points for your rolls, it would make sense to give seven times as many points for five singlets than for a pair, and twice the number of points for singlets than for a triplet. Four and five equals should probably give some special bonus.

* This is about as complex Monte Carlo simulations you can sensibly do with spreadsheet formulas, unless you know a lot about combinatorics. In the next episode we will have a look at writing JavaScript code to do Monte Carlo simulations on drawing of cards.
