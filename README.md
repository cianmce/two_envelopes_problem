# two_envelopes_problem
https://en.wikipedia.org/wiki/Two_envelopes_problem

## Paradox

You are given two indistinguishable envelopes, each of which contains a positive sum of money. One envelope contains twice as much as the other. You may pick one envelope and keep whatever amount it contains. You pick one envelope at random but before you open it you are given the chance to take the other envelope instead

If there's 100 in the first envelope, you can say there is either 200 or 50 in the other envelope. Changing would result in you either gaining 100 or losing 50 which would result in an expected value gain of
```
(1/2)(2X) + (1/2)(X/2) = (5X/4)
```

Meaning there's a net gain by switching

## How to run:
```
bundle exec ruby envelopes.rb --count=100000 --verbose=false --randomize=true
```
