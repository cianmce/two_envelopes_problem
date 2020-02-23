# Two envelopes problem

## Paradox

In the [two envelopes problem, also known as the exchange paradox](https://en.wikipedia.org/wiki/Two_envelopes_problem), you are given two indistinguishable envelopes, each of which contains a positive sum of money. One envelope contains twice as much as the other. You may pick one envelope and keep whatever amount it contains. You pick one envelope at random but before you open it you are given the chance to take the other envelope instead

If there's 100 in the first envelope, you can say there is either 200 or 50 in the other envelope. Changing would result in you either gaining 100 or losing 50 which would result in an expected value gain of
```
(1/2)(2X) + (1/2)(X/2) = (5X/4)
```

Meaning there appears to be a net gain by switching

## How to run:
```
bundle exec ruby envelopes.rb --count=100000 --verbose=false --randomize=true
```

### Sample output:
```
$ bundle exec ruby envelopes.rb --count=10000000 --verbose=false --randomize=true
Randomize values: true
Total iterations: 10,000,000
I've made €75,086,029,600 from changing vs €75,090,138,140 if I stuck
Gain: -0.0055%
Time: 4.708215 seconds
```
