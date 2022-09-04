# jointprob, section D

The [jointprob community](https://scicloj.github.io/docs/community/groups/jointprob/) is a Bayesian data analysis study group.
The goal is to work through Richard McELreath's *Rethinking Statistics, 2nd Ed*.
It is sponsored by the [SciClo project](https://scicloj.github.io) and lead by Daniel Slutsky.

## meeting1.Rmd

Rmarkdown file that I presented in the first meeting of section D of the on Saturday, August 20, 2022. 
I covered chapter 1 of McElreath and chapter 1-4 of Grolemund and Wickham [*R for Data Science*](https://bookdown.org/roy_schumacher/r4ds/).

## meeting2b.Rmd

This is the edited version of the Rmarkdown file that I presented in the second meeting of section D of the on Saturday, September 3, 2022. 
Daniel Slutsky gave a great 80-minute presentation computating the posterior distrubtion, which set me up well to present how to use grid approximation to estimate the posterior distribution in R.

I included the suggested exercises from Chapter 2 of McElreath's *Rethinking Statistics, 2nd Ed*. 
Next, I ventured off and tried a triangular distribution from the `extraDistr` package as a prior.

I added some embelleshments like normalization of the prior and summing of the prior and the likelihood as saniety checks.
These embellishments were not required to compute the correct posterior, but they deepened the understanding of what was happening.

