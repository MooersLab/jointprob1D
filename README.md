# jointprob, section D

The [jointprob community](https://scicloj.github.io/docs/community/groups/jointprob/) is a Bayesian data analysis study group.
The goal has to work through Richard McELreath's *Rethinking Statistics, 2nd Ed*.
As of January 7, 2023, the focus is shifting to  *Bayesian Modeling and Computation In Python*.
Ravin Kumar, one of the three authors of this book, attended the January 7th meeting.
The book is available on-line for free

The [SciClo project](https://scicloj.github.io) sponsors jointprob. 
Daniel Slutsky leads the meetings.


These are the quiding principles for the group (Thanks to Ryan Onsinger!):

- *No experts.* We do not assume that anybody is an expert in the field. We come to learn together with a student mindset.

- *A clear path.* We will be very thoughtful about the agenda and where we wish to go. We will continually rethink and adapt our pathway going there.

- *Confused together.* It is just fine to be confused. We will be there together and seek clarity together.

- *Being active.* We encourage members to learn independently and take on projects. In a sense, its purpose is (also) to support those individual journeys.

- *Mutual curiosity.* We make serious efforts to be inclusive to participants of various backgrounds. The different perspectives of our friends are part of what we wish to learn.






## meeting1.Rmd

Rmarkdown file that I presented in the first meeting of section D of the on Saturday, August 20, 2022. 
I covered chapter 1 of McElreath and chapter 1-4 of Grolemund and Wickham [*R for Data Science*](https://bookdown.org/roy_schumacher/r4ds/).

## meeting2b.Rmd

I edited this Rmarkdown file that I presented in the second meeting of section D of the on Saturday, September 3, 2022. 
Daniel Slutsky gave an excellent 80-minute presentation about computing the posterior distribution, which set me up well to present how to use grid approximation to estimate the posterior distribution in R.

I included the suggested exercises from Chapter 2 of McElreath's *Rethinking Statistics, 2nd Ed*. 
Next, I ventured off and tried a triangular distribution from the `extraDistr` package as a prior.

I added some embellishments like the normalization of the prior and the summing of the prior and the likelihood as sanity checks.
These embellishments were not required to compute the correct posterior, but they deepened the understanding of what was happening.

## meeting3b.Rmd

I presented this Rmarkdown file in the third meeting of section D on Saturday, September 17, 2202.
It recaps the grid approximation presentation and then covers the two other *motors* of the Bayesian data analysis engine: quadratic approximation and Markov Chain Monte Carlo.


## meetingX.ipynb

I presented this Jupyter notebook on infomration theory at the Christmas Eve meeting of jointprob.

