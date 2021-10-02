# Prime Factors Scatch

A [Scratch](https://scratch.mit.edu) project to calculate [Prime Factors in a TDD style](https://scratch.mit.edu/projects/556820395).

## Background

I was discussing Prime Factors with my son and had done a coding kata to calculate these in Python. 

I was interested to see whether a TDD approach could be used for recreating the project in Scratch and found this helpful project that gave a lot of helpful guidance: [Ross Sharper Scratch TDD](https://github.com/rossharper/ScratchTDD).

## Comparing Lists in Scratch

One thing I found at the time was comparing two lists did not seem reliable. I was comparing a list of expected factors with the calculated factors and although the content looked identical the equality check seemed to return false (it had worked previously and I don't know what I changed!).

I changed the check to compare each item in turn and that worked fine.
