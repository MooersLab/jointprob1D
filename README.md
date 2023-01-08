# jointprob

The [jointprob community](https://scicloj.github.io/docs/community/groups/jointprob/) is a Bayesian data analysis study group.
The goal has to work through Richard McElreath's *Rethinking Statistics, 2nd Ed*.
We met on Sataurdays for two hours once every two weeks.
We made it through chapter 7.
 
There were initially about 30 people interested in jointprob last summer.
Four parallel sections were held to accommodate different schedules and time zones.
I participated in Section D, which met on Satruadys
Secion D was the last section left standing as of December.
We were down to 4-6 participants.
It was time for a refresh.

The consensus was to shift our focus to the book *Bayesian Modeling and Computation In Python (BMCP)* by Osvaldo Martin, Ravin Kumar, and Junpeng Lao.
We had an organizing meeting on January 7th.
24 people attended. 

Ravin Kumar also attended and spoke for about an hour.
He provided invaluable insights about how best to read his book.
He stressed that his book emphasizes the practice side before the theory.
He recommened McElreath's book for the theory.
The book uses three probabilitistic programming languages: PyMC, tensorflow probability, and numpyro.

Ravin is a mechanical enigineer who quit Space-X to spend time teaching himself BDA.
He started contribuing to the [PyMC3](https://www.pymc.io/welcome.html) progect on GitHub.
He then got hired at Google to apply BDA to various problems.
He enthusiasm for BDA is contagious.

The [book](https://bayesiancomputationbook.com/welcome.html) is available on-line for free.
The [code](https://github.com/BayesianModelingandComputationInPython/BookCode_Edition1) for the book is located on Github.
The code in the book uses PyMC3, but the current version of pymc is version 5.
The code has not been translated to PyMC5.
The pymc community has a [discourse channel](https://discourse.pymc.io/) and an upcomming [webinar](https://pymcon.com/about) series. 
They had a similar webinar [series](https://www.youtube.com/watch?v=UznM_-_760Y&list=PLD1x-BW9UdeHN2vwR6kIApJATd2jZzeya&index=1) in 2020. 

The first four chapters are the heart of the book.
They are all that you need to start practicing BDA.
Chapters 5 - 8 are specialized topics that cover areas that most people will to use.
Chapters 9, 10, and 11 contain appendix material.

- 1 & 2 Basics
- 3 & 4 Linear models and their applications
- 5 Splines
- 6 Time series
- 7 BART
- 8 ABC
- 9 Bayeisan workflow
- 10 PPLs
- 11 Appendical Topics (many theory topics are nicely summarized here )

Daniel Slutsky leads the meetings.
Ryan Onsinger is the community organizer.
The SciCloj community sponsers the jointprob events.
This community is developing scientific computing tools in Clojure.


These are the quiding principles for the group (Thanks to Ryan Onsinger!):

- *No experts.* We do not assume that anybody is an expert in the field. We come to learn together with a student mindset.

- *A clear path.* We will be very thoughtful about the agenda and where we wish to go. We will continually rethink and adapt our pathway going there.

- *Confused together.* It is just fine to be confused. We will be there together and seek clarity together.

- *Being active.* We encourage members to learn independently and take on projects. In a sense, its purpose is (also) to support those individual journeys.

- *Mutual curiosity.* We make serious efforts to be inclusive to participants of various backgrounds. The different perspectives of our friends are part of what we wish to learn.

You are not required to do the reading in advance, but you will get more out of the meetings if you do so.
You will also get more out of the meetings by presenting a porition of the reading: the best way to learn to try teach to the material.
This takes preparatory time. I found that 6-8 houres was required to put together a 30-40 minute talk.




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


## SectionD10.ipynb

I presented this Jupyter notebook on information theory at the Christmas Eve meeting of jointprob.
I included material from chapter 11 of BMCP.
One code cell does not work.

