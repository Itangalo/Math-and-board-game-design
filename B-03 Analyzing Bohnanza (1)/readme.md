# Episode B-3: Analyzing Bohnanza, part 1

* Link to video: (not yet recorded)
* Link to presentation: (not yet created)
* Link to spreadsheet: (not yet created)

## (only sketches so far)

In the game [Bohnanza](https://boardgamegeek.com/boardgame/11/bohnanza) you plant beans and sell them to get bean coins, which are more or less victory points. There are several types of beans, and you get paid more if you have more beans of the same type. (There is more to the game, but for our purposes this will do.) We will have a closer look at this game, and see how we can use math to analyze how well different types of beans pay off.

Some bean types are more common, while others are rare. The more common a bean is, the more cards you'll have to collect to get the same amount of bean coins. (Look at a few cards.)

The influx of cards is more or less constant, which means that an important factor in the game is to have a high cards to bean coins conversion ratio. For the garden bean, being the most rare of the bean types, the conversion ratio is 1:1. For other bean types we can see that the conversion ratio is lower for few cards and grows to about 1:2.

My guess is that this conversion ratio corresponds pretty well to how difficult it is to collect the given number of cards: If it is twice as hard to get seven cards than it is to get four cards, the conversion ratio when selling seven cards is roughly twice as that you get when selling four cards. If my guess is wrong, we can find a good candidate for a dominant strategy in Bohnanza: Focus on the combinations which have a substantial better convertion ration, compared to how difficult the combination is to get. (Now, this isn't the whole truth. There is trading going on in the game, and cards are also lost when coins are collected -- which means that the availability of the cards shifts as the game progresses.)

As it happens, we have a tool for estimating how easy it is to get your hands on, say, ten blue beans. I will use it to investigate if some bean types are overprized or underprized. This is something I expect that the game designers did when developing the game, but it is also possible that they started off with gut-feeling guesses and adjusted the numbers based on extensive playtesting. In any case, the things I will investigate now _could_ have been done in a similar way during game development. Note that this is the first time I'm trying this. I will try to think aloud while digging around in the numbers, to give a feeling of one way the mathematics of a game could be explored as it actually happens. I don't claim that this is the best way, and I assume that I would do it in a more efficient way if I do it for a second time.

We'll start by just adding some data from the Bohnanza cards. The actual exploring of the mathematics in the game will be in the next episode.
