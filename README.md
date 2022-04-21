# Math and board game design

This is the project page for some videos, notes, code and other things that has to do with using mathematics in board game design.

The project is still in pre-alpha, meaning that there are sketches of content but not anything to look at. The idea is to post screencasts on YouTube, as the main medium, and use this project page to collect links to videos as well as posting any notes and other things relating to the videos. Later videos will most likely contain some code, and then code will be available here as well.

The project has an issue queue, where ideas and suggestions are very welcome. You will need an account on GitHub to post issues, which is free (and often a good thing to have anyway if you will share code with others in the future).

## Roadmap

I want to start with real basics, and I want to keep videos to 10 minutes or less. (I will probably fail on both, but ambitions are good.)

I imagine that the first videos will be something like this. **Feel free to post your own ideas in [the issue queue](https://github.com/Itangalo/Math-and-board-game-design/issues)!** I'd love to hear what you would like to see when it comes to applying mathematics to board game design.


### A: The introduction

1. **Math is everything. Math is nothing.** Why mathematics will save you loads of time when creating board games. And why mathematics won't tell you if a game is good.
2. **Basic probability calculations.** Some very basic examples of looking at (and calculating) probabilities for some dice and card events.
3. **Introducing Monte Carlo simulations.** Some pretty basic examples of dice and card events where calculating probabilities becomes gets really complex. The idea of Monte Carlo simulations: simulating the individual random events and looking at the result, and then repeating a gazillion times.
4. **Describing probability.** The concepts of (arithmetic) mean, expectation value, median and mode, and why/when they may be useful in board game design. The concepts of percentiles and probability distribution, to look at how likely/unlikely events are.
5. **Playing with dice.** Using spreadsheets to find probabilites for getting 1 to 5 equals when rolling five standard dice.

### B: Introduction to using JavaScript with spreadsheets to estimate probabilities

1. **Drawing cards with code (1).** A first look at how to look find probabilities of drawing a certain number of special cards from a deck – using JavaScript attached to a Google spreadsheet.
2. **Drawing cards with code (2).** Modifying the code in the previous episode, to get a more flexible tool for looking at probabilities when drawing cards.
3. **Analyzing Bohnanza.** Applying some mathematics to decompose an aspect or two of the game Bohnanza. Why do the cards pay off differently, and can we find cards that are better than others?

### C: Other stuff

Not sketched out yet.

* **Non-standard dice rolls.** Some examples of how to get statistics for non-standard dice (such as dice with negative numbers or results that allow bonus rolls).
* **Analyzing The Mind.** Making some assumptions on how players behave when playing The Mind, we can model the game pretty well and find out how likely it is that players get to certain levels.
* **Looking at normal distribution.** The sum of 3d6, and most other sums of 3 or more dice, is distributed in a bell curve. This has some useful implications if using the rolls for skill checks and the like.


### D: Other lose ideas

Ideas for episodes further down the line.

* **Letters to the editor.** Questions and situations to analyze provided by you and others. ([Post in the issue queue right away!](https://github.com/Itangalo/Math-and-board-game-design/issues))
* **Balancing an economy.** How much should a resource cost? Some words on finding something to anchor on and using math to determine prices -- be it in terms of money, action points or something else.
* **Useful spreadsheet tricks.** There are tonnes of useful tricks to simplify your work with spreadsheets.


## Who am I?

My name is Johan Falk. I like tea, baking bread, mathematics, board games and playing guitar -- not necessarily in that order. I live in Sweden with a wife and two kids, and I work with mathematics education on a national level. December 2019 I finally began a serious attempt to create a board game of my own ([Altrix](https://github.com/Itangalo/Altrix)). It lead to a ton of calculations and eventually a framework for doing [bot-driven playtesting](https://github.com/Itangalo/Bot-Playtesting-Toolkit).

I hang around in [the BGDL Facebook group](https://www.facebook.com/groups/BGDLCommunity) and [a Swedish group for board game developers](https://www.facebook.com/groups/382791418411976). Online I go by the name _Itangalo_ or _magister Falk_.
