I Saw this tweet...

https://twitter.com/LeedsMathsJam/status/1032002505297874945

![instructions](https://pbs.twimg.com/media/DlJozTSXoAIz_Lv.jpg:large)

...and thought I'd give it a go.

The puzzle is very similar to the [Countdown numbers game](http://wiki.apterous.org/Numbers_game). So, I thought I could just adapt [an earlier project](https://github.com/taylorjg/Countdown) to find the answer. But, the best answer I could get was 22.

However, Countdown has this rule:

> no fractional numbers or negative numbers may appear as part of a solution

It turns out that to find a solution to this 'Make 21' puzzle, we need to allow the use of fractional numbers. So I made a couple of tweaks and finally got an answer:

```
(6.0/(1.0-(5.0/7.0))) = 21.0
```
