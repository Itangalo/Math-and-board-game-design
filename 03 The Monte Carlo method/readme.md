# Episode 3: The Monte Carlo method

* Link to video: (not yet recorded)
* Link to presentation: (not yet created)
* Link to spreadsheet: (not yet created)

## (only sketches so far)

* We've seen some basic examples of how to calculate probabilities for dice rolls and drawing cards. But these quickly get _very_ complex, even for things that look easy on the surface. What are the chances of rolling a straight with five dice? Of rolling exactly a triplet?
* Instead of calculating probabilities, they can be _estimated_ using something called the Monte Carlo method. This is a fancy word for usig a computer for trying something _a lot_ of times and check how many times it succeeds. The results aren't exact in the way you get with calculations by hand, but they are good enough for practical purposes.
* Example: Using a spreadsheet to find the average value of 1d4 + 1d6 + 1d8 + 1d10 + 1d12 + 1d20. (Including some useful spreadsheet functions.)
* Looking at the average as the number of rolls increase.
* Note that the values for each roll changes with each edit in the spreadsheet, while the average value barely changes. This is because we use a large number of rolls, and the results even out over time. This is a powerful property of average values – if players make a large number of rolls, we can feel pretty certain that the average (and also the total sum) will be fairly close to a given value.
* We will be doing more calculations in spreadsheets when possible, and more complex calculations than this one, but we will also do some coding to cover things that are more complex.
