# Stat_435_Homework_2

1) Another interval for π is the logit confidence interval. This method finds a Wald
confidence interval for log (π/(1 − π)), which is known as the logit transformation,
and then transforms the endpoints back into an interval for π. The resulting interval
is
exp
[
log
( ˆπ
1−ˆπ
)
± Z1−α/2
√ 1
nˆπ(1−ˆπ)
]
1 + exp
[
log
( ˆπ
1−ˆπ
)
± Z1−α/2
√ 1
nˆπ(1−ˆπ)
]
(a) What is the numerical range for log (π/(1 − π))? After transforming the end-
points back using the exp(·)/[1 + exp(·)] transformation, what is the new numer-
ical range? Why is this new numerical range ideal?
Analyzing a binary response, part 1: introduction 53
(b) Verify the estimated variance of log (ˆπ/(1 − ˆπ)) is [nˆπ(1 − ˆπ)]−1 by using the
delta method (see Appendix B.4.2).
(c) Verify the 95% logit confidence interval is 0.1583 < π < 0.7026 when n = 10 and
w = 4. Note that binom.confint() calculates this interval using the methods
= "logit" argument value.

2) Before a placekicker attempts a field goal in a pressure situation, an opposing team
may call a time-out. The purpose of this time-out is to give the kicker more time to
think about the attempt in the hopes that this extra time will cause him to become
more nervous and lower his probability of success. This strategy is often referred to
as “icing the kicker.” Berry and Wood (2004) collected data from the 2002 and 2003
National Football League seasons to investigate whether or not the strategy actually
lowers the probability of success when implemented. Table 1.7 contains the results
from the 31-40 yard field goals during these seasons under pressure situations (attempt
is in the last 3 minutes of a game and a successful field goal causes a lead change).
Complete the following:
(a) Calculate the Wald and Agresti-Caffo confidence intervals for the difference in
probabilities of success conditioning on the strategy. Interpret the intervals.
(b) Perform a score test, Pearson chi-square test, and LRT to test for the equality
of the success probabilities.
(c) Estimate the relative risk and calculate the corresponding confidence interval for
it. Interpret the results.
(d) Estimate the odds ratio and calculate the corresponding confidence interval for
it. Interpret the results.
(e) Is there sufficient evidence to conclude that icing the kicker is a good strategy to
follow? Explain.

3) Aseffa et al. (1998) examine the prevalence of HIV among women visiting health
care clinics in northwest Ethiopia. Along with testing individuals for HIV, additional
information was collected on each woman such as condom use. Table 1.8 gives a
contingency table summarizing the data.
(a) Calculate the Wald and Agresti-Caffo confidence intervals for the difference in
probabilities of being HIV positive based on condom use. Interpret the intervals.
(b) Perform a score test, Pearson chi-square test, and LRT to test for the equality
of the success probabilities.
(c) Estimate the odds ratio and calculate the corresponding confidence interval for
it. Interpret the estimate and the interval.

HIV vaccine results from the modified intent-to-treat data. Data source is
Rerks-Ngarm et al. (2009).
Response
HIV No HIV Total
Treatment Vaccine 51 8,146 8,197
Placebo 74 8,124 8,198
Total 125 16,270 16,395
