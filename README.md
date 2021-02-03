# Mobile-Games-AB-Testing-with-Cookie-Cats
## Purpose of analysis:

To understand if we have better retention rate when moving the in-app purchases gate from level 30 to level 40?

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

But where should the gates be placed? Initially the first gate was placed at level 30, but in this notebook we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we will look at the impact on player retention. But before we get to that, a key step before undertaking any analysis is understanding the data. So let's load it in and take a look!


## Method of analysis:

1.Probability density function(pdf) plot

2.Bootstrap resampling

3.Calculating the probability that D1 vs D7 retention is greater when the gate is at level 30
