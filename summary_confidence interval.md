

Ways to think about confidence intervals:

**A confidence interval is a set of hypotheses** A 100 * ( 1 - \alpha) confidence interval _excludes implausible hypotheses_ (where implausibility is defined by \alpha). A confidence interval _contains hypotheses that you would not reject_ at the \alpha significance level. So, a 95% CI excludes hypotheses rejectable at p=.05 and includes hypotheses not-rejectable at p=.05.


**A confidence interval summarizes the variability in estimates** from the sampling distribution of such estimates. It summarizes variability in the sampling distribution of estimates --- thus summarizing sample-to-sample variability in those estimates. In this way it --- via the standard error of an estimator --- answers the question: "How might my estimates vary from sample to sample (or experiment to experiment)?"

Terms:
 - Coverage (rate) of a confidence interval: the error rate of a confidence interval.
 - Coverage interval: an interval describing the percentiles of variable --- a descriptive summary. The middle 50% coverage interval of a variable is often called the Interquartile range, for example.
 - Confidence interval: (see above)

We can *invert a hypothesis test* to create a confidence interval by testing many different specific hypotheses (or by searching for which hypotheses would have p-values just at \alpha).

We can *invert a confidence interval* to create a hypothesis test in two ways: 
 - First, and most simply, if a hypothesized value for a parameter is *outside* the confidence interval then we know that if we were to test that hypothesis the p-value would be less than (100 - the confidence level)/100: that is if a hypothesized value is outside a 95% confidence interval then we know that its p-value would be less than .05.  (By "parameter" I'm referring to the kind of thing we hypothesize about: an unknown and unobservable characteristic of a population or an experimental pool --- like differences in potential outcomes in an experimental pool or like a population level relationship). We also know that hypothesized values *inside* the interval would have p>.05. This knowledge comes from the first interpretation of a confidence interval in terms of hypothesis tests.
 - Second, we can ask about how strange it would be to see the hypothesized value in our sampling distribution. Geyer and Fox teach us how to do this but remind us that this is pretty weird: after all a null hypothesis requires a distribution **of a test statistic reflecting that hypothesis** and a sampling distribution reflects an estimator not a test statistic.

Why does the bootstrap work? You all got this nicely in your explorations: sampling with replacement means that each person in the sample has an equal probability (or at least known) of falling into the bootstrap re-sample. If the sample itself was drawn in such a way as to allocate known (and maybe even equal) probability to each person in the population, then a sample from the sample is a sample from the population. This means that bootstrap standard errors and confidence intervals really do tell us a lot about what would happen if we were to actually draw many new samples from the same population.

One subtle point about samples representing populations: in the social world we have history. This means that a simple random sample of people in Illinois today need not exactly represent the population tomorrow --- for only one example, the attitudes of people the day before Sept 11, 2001 differed from the attitudes of people the day after Sept 11, 2001 because the population of attitudes changed.
