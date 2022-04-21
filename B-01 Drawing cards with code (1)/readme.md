# Episode B-1: Drawing cards with code, part 1

Link to video: (not yet recorded)
Link to presentation: (not yet created)
Link to spreadsheet: (not yet created)

## (only sketches so far)

* This is the first episode where we will look at using code to do math for board game design. Since we have already done the easiest cases, there will be a bit of a jump here. In this episode we will mostly look at code that is pre-written, and investigate what it does and how we can use it. Learning how to code takes a lot of time and can be very frustrating at times. But coding can also be tremendously rewarding, and it opens up a lot of possibilities when it comes to simulating things in board game development.

* The scenario we're simulating here is a deck of 60 cards, in which there are 10 cards with gold coins, and we want to know the chances of getting exactly 2 of these when drawing 5 cards. In the next episode we will do this more generally, but let's start here.
* Why is this so much more difficult to simulate than when we rolled five dice and counted the number of equals? One of the key differences is that we now have something called _dependent probability_ – the probability associated with the second card depends on what the first card shows. This makes calculating (and simulating) probabilities a bit messy. It is definitely possible to do even with pen an paper, but you'll need a lot of skills and even then you might ending up a factor of two off the proper value and not even realizing it.

* Spreadsheet: Open the Apps Script window. Copy over already written code from GitHub. Save, call the function from the spreadsheet.
* Apps Script: These are variables storing values for the script – in this case numbers. Here is a loop, running our scenario ten thousand times. Every time the loop runs, a deck is prepared, shuffled, and then five cards are drawn. If there is exactly three gold coins, the number of successes is increased by one. When all the loops are finished, the ratio of successes is returned.

Note: Separate functions for shuffling and for counting occurances in the drawn hand. These are mentioned, but not explained – ignoring the inner workings of functions and just looking at what it achieves is an important part of programming.

* We can change the variable values, and then the returned values in the spreadsheet are updated. But there are better ways of doing this.
