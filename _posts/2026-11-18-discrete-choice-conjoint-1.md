---
layout: post
title: Introduction to Discrete Choice Conjoint
subtitle: Estimating preference utilities and willingness to pay for product attributes
editor_options: 
  markdown: 
    wrap: 72
---

Over the past year, I have worked with clients on a range of projects.
Two recently involved estimation of preference utilities and willingness
to pay for product or package attributes through choice trade-off
surveys. I drew on prior experience in market research consulting at
Applied Decision Analysis and R programming skills. I also acquired new
knowledge through literature review.

This post is the first in a series on this topic, including:

1\. Introduction to Discrete Choice Experiments

2\. Design and Analysis of Discrete Choice Experiments in R

3\. Discrete Choice Experiments for Establishing the Smallest Worthwhile
Effect of Treatment

Discrete choice experiments (DCE) belong to the field of conjoint
analysis survey methods designed to estimate relative importance and
preferences for product attributes "considered conjointly" (thus,
conjoint). If asked directly, someone may be able to report the relative
importance of different attributes. For example, someone might say,
"When deciding which medication to take, I would choose one with fewer
doses despite risk of stomach upset." However, they are unlikely to be
able to quantify the strength of this preference, how much more they
would be willing to pay for a specific improvement, or whether other
factors might influence their decision.

In a DCE, attribute levels (e.g., dosing, side effects, and cost) are
shown together in a series choice sets. For each set, a respondent is
asked to specify their preferred choice. An example building on the
medication features is shown below, assuming a common (moderate)
improvement in clinical outcome.

| Attribute | Choice A | Choice B |
|------------------------|------------------------|------------------------|
| Improvement in outcome | 4 in 5 people have symptom relief | 4 in 5 people have symptom relief |
| Risk of stomach upset | High | Low |
| Doses per day | 1 | 2 |
| Price per month in dollars | 10 | 15 |

A series of these choice sets are presented, varying levels according to
specifications. Common options in medical research include Bayesian
D-Efficient and blocked fractional factorial designs (Kessels et al
2011; Jaynes et al 2014; Vanniyasingam et al 2016). The number of choice
sets and respondents may be determined using power estimation or
simulations (Assele et al 2023; de Bekker-Grob 2015).

It is possible to add a layer to these surveys to understand what
outside factors may influence stated preferences. For example, one of my
clients randomized respondents to salience intervention or control. Half
of the respondents saw a statement instructing them to think about a
specific attribute before beginning their set of choice tasks in the
survey.

Checklists developed by the International Society for Pharmacoeconomics
and Outcomes Research (ISPOR) support the process of designing and
evaluating results from conjoint-analysis studies in health research
(Bridges et al 2011; Hauber et al 2016).

References

Samson Yaekob Assele, Michel Meulders, Martina Vandebroek, Sample size
selection for discrete choice experiments using design features, Journal
of Choice Modelling, Volume 49, 2023, 100436, ISSN 1755-5345,
<https://doi.org/10.1016/j.jocm.2023.100436>.

John F.P. Bridges, A. Brett Hauber, Deborah Marshall, Andrew Lloyd, Lisa
A. Prosser, Dean A. Regier, F. Reed Johnson, Josephine Mauskopf,
Conjoint Analysis Applications in Health—a Checklist: A Report of the
ISPOR Good Research Practices for Conjoint Analysis Task Force, Value in
Health, Volume 14, Issue 4, 2011, Pages 403-413, ISSN 1098-3015,
<https://doi.org/10.1016/j.jval.2010.11.013>.

de Bekker-Grob EW, Donkers B, Jonker MF, Stolk EA. Sample Size
Requirements for Discrete-Choice Experiments in Healthcare: a Practical
Guide. Patient. 2015 Oct;8(5):373-84. doi: 10.1007/s40271-015-0118-z.
PMID: 25726010; PMCID: PMC4575371.

A. Brett Hauber, Juan Marcos González, Catharina G.M.
Groothuis-Oudshoorn, Thomas Prior, Deborah A. Marshall, Charles
Cunningham, Maarten J. IJzerman, John F.P. Bridges, Statistical Methods
for the Analysis of Discrete Choice Experiments: A Report of the ISPOR
Conjoint Analysis Good Research Practices Task Force, Value in Health,
Volume 19, Issue 4, 2016, Pages 300-315, ISSN 1098-3015,
<https://doi.org/10.1016/j.jval.2016.04.004>.

Jaynes, J., Wong, W. -K., and Xu, H. (2016) Using blocked fractional
factorial designs to construct discrete choice experiments for
healthcare studies. Statist. Med., 35: 2543–2560. doi: 10.1002/sim.6882.
<https://doi.org/10.1002/sim.6882>

Roselinde Kessels, Bradley Jones, Peter Goos, Bayesian optimal designs
for discrete choice experiments with partial profiles, Journal of Choice
Modelling, Volume 4, Issue 3, 2011, Pages 52-74, ISSN 1755-5345,
[https://doi.org/10.1016/S1755-5345(13)70042-3](https://doi.org/10.1016/S1755-5345(13)70042-3){.uri}.

Vanniyasingam, Thuva & Cunningham, Charles & Foster, Gary & Thabane,
Lehana. (2016). Simulation study to determine the impact of different
design features on design efficiency in discrete choice experiments. BMJ
Open. 6. e011985.
[10.1136/bmjopen-2016-011985](https://doi.org/10.1136/bmjopen-2016-011985).

This post was developed without the support of Generative AI.
