# Episode 4: Ways of looking at averages

* Link to video: (not yet recorded)
* Link to presentation: (not yet created)
* Link to spreadsheet: (not yet created)

## (only sketches so far)

In the previous episode we looked at the average sum of some dice and found it to be XX. In this episode we will look closer at the dice results and dig into some more nuanced ways of them:

* The **arithmetic mean** (often just _mean_) is the average of all values, which is useful if you want to look at the sum of many cases. This is what we looked at in the previous episode.
* This arithmetic mean is closely related to something called **expectation value**. The mean in based on actual measurements and thus may vary, in particular if you have small data sets. The expectation value is the theoretical mean, and you can think of it as the mean based on an infinite amount of measurements.
* The **mode** is the most common value – if you want to find a single typical case, the mode is the one to use.
* The **median** is the middle value, cutting the data set in two halves – one with values at or above the median, one with values at or below. I've had a hard time finding good examples of when the median is useful in board game design, but it doesn't hurt to know about it.

(Spreadsheet: Getting mode, average and median for the data set.)

Things become more interesting when looking at **percentiles** and approximations of **probability distribution**.

* **Percentiles** work like the median, but instead of cutting the data in halves, the 12th percentile is the value cuttning the data in 12 percent above and 88 percent below. Thus, the 50th percentile is the same thing as the mean.

(Spreadsheet: Getting percentiles 0 to 100 of the data set in a neat way.)

* **A probability distribution** is something describing how the data is distributed over all possible outcomes – in our case how often different sums occur. For board game design purposes, plotting percentile values is a good way of approximating a probability distribution.

(Spreadsheet: Plotting the probability distribution.)
