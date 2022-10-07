# Dice Wars Reloaded

This repository contains my modifications to gamedesign.jp's DICEWARS
game.

The original DICEWARS is [here](https://www.gamedesign.jp/games/dicewars/).

I have archived the orginial game
[here](https://parke.github.io/dicewars/gamedesign.jp/).

Dice Wars Reloaded (my modified version of DICEWARS) is
[here](https://parke.github.io/dicewars/reloaded/).

The original DICEWARS game is copyright by gamedesign.jp.

### My modifications:

*  Changed the colors to a dark theme.
*  Removed the dice roll animation to speed up the game.
*  Disabled sound effects.

###  Why is Dice Wars still worth playing (20+ years later)?

*  Dice Wars is a radical simplification of the board game Risk.
*  Dice Wars offers a quick yet satisfying tactical challenge.
*  Maps are randomly generated so every game is unique.
*  Dice Wars nicely blends randomness versus predictability.
*  Due to the randomness, when playing Dice Wars, you must make strategic risk manegement decisions.
*  You will win by keeping the computer players in balance until you can seize a decisive advantage.

###  Understand your income

At the end of each turn, the game will calculate the size of your
largest contiguous territory.  (These size numbers are always
displayed at the bottom of the screen.)  You will receive one
additional die for each territory in your largest contiguous
territory.

Therefore, it is to your advantage to connect all your territories
into one contiguous group, and to keep them connected.  Similarly, it
is to your advantage, when reasonably possible, to spilt your
opponents into several non-contiguous territories, as this will
greatly reduce their income.

Your new dice will be allocated randomly across all your territories.
You do not control where new dice appear.  Each territory can hold at
most 8 dice.  When all your territories have 8 dice, extra dice will
be stockpiled, up to a maximum stockpile size of 64.

###  Understand how the computer players move

Your odds of playing well will greatly increase if you understand how
the computer players will move.

Due to the animation speed of the original Dicewars, it can be
difficult to learn how the computer moves.  (And in my Reloaded
version, the animation is much, much faster.)

The truth is, you don't need to watch every move the computer makes.
You simply need to understand the principles that will guide the
actions of the computer players.

Each turn, each computer player will decide to use one of two
different strategies.  I call these strategies "Phase One" and "Phase
Two".

####  Phase One

In Phase One:  If the computer player has an equal or greater number
of dice in a territory, compared to a neighboring territory, the
computer will attack that neighboring territory.

In other words, in Phase One:  A computer player will never attack
"uphill", but will always attack "level" or "downhill".

####  Phase Two

Once one player (human or computer) establishes a dominant position,
then all the non-dominant computer players will switch to the Phase
Two strategy.  (A "dominant position" approximately means controlling
somewhere between 35% to 50% of all territories.)

In Phase Two:  Non-dominant computer players will only attack the
dominant player.  As with Phase One, only "level" or "downhill"
attacks will happen.  Even in Phase Two, no computer player will ever
attack "uphill".

###  That's it!

There may be a few more subtleties to how the computer players move,
but the above outline should enable you to learn to play well.
