---
title       : Assessing Accuracy of Pre-Election Polls
subtitle    : 2008 - 2012
author      : MJ Cho
job         : PPRG Presentation
logo        : logo.png
framework   : io2012               # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js         # {highlight.js, prettify, highlight}
hitheme     : tomorrow             # 
widgets     : [mathjax, bootstrap, quiz] # {mathjax, quiz, bootstrap}
mode        : selfcontained        # {standalone, draft}
knit        : slidify::knit2slides

--- # Outline



--- #RQ

<style>
body {
  background-color: #000;
}
.quiz-option label{
  display: inline;
  font-size: 1em;
}
ul.nav li::before { content: ""; }  
ul.nav li{ font-size: 18px; line-height: 24px;}
</style>

## Research Questions

>- 1. Are consumers of online news exercising selectivity in their news choices?
   - The partisan polarization hypothesis: active selectivity and motivated exposure
   - How strong is the tendency of the partisans to self-select into distinct audiences?
>- 2. Does the news content matter?
   - Hard vs. soft news
   - Is the effect of selectivity stronger for subjects where partisan divisions are intense?
>- 3. Doe attentiveness matter?
   - The more attentive vs. the less attentive and the partisans vs. the nonpartisans
   - Political interest$*$partisanship

--- #Why1

## The "So What" Question

So **why** should we care about answering these questions?

>- 1. Is the public polarized?
   - We already know that the elites/activists are polarized!
   - Does increased selectivity among news consumers reflect increased level of interparty animus?
>- 2. What are the implications of a changing media environment?
   - From an overtly neutral to an increasingly diverse media environment: cable news and the Internet
   - We already have evidences of media bias for mainstream media based on surveys, how about online news then?
   - Does the Internet narrow users' political horizen: the echo chamber and the Daily Me?

--- #Why2

## The "So What" Question

So **why** should we care about answering these questions?

>- 3. What are the implications of an increasingly polarized news audience?
   - How does a polarized audience affect the media industry and its way of exercising journalism?
   - How does a polarized audience affect elite behavior and political campaigns?

--- #Literature

## What is already known in the literature?

>- 1. Gunther et al. (2001), Congenial public, contrary press, and biased estimates of the climate of opinion
   - The "hostile media" phenomenon: demonstrates selectivity in news choices
   - People who are highly involved in an issue tend to see news coverage of that issue as biased
>- 2. Pfau et al. (2007), Mediating the vote: The changing media landscape in US presidential campaigns
   - Provided evidence of differential media use among partisans during the 2000 and 2004 campaigns
>- 3. Gentzkow & Shapiro (2006),  Media bias and reputation
   - Consumers infer the quality of a information source based on the conformity between what the source reports and their expectations.
   - Bayesian model of media bias that makes predictions consistent with empirical evidence

--- {class: class, tpl: tabs}

## Method

*** {class: active, id: Design}

- 1. Online experiment
- 2. 4 source labels (Fox, NPR, CNN, and BBC) with a "Can't say" option
- 3. 6 subject matters (Politics, Race relations, Iraq, Sports, Crime, and Travel) across two dimensions (hard and soft)
- 4. Control condition in which all source labels were deleted

*** {id: Sample}

- 1. Nationally representative sample of 1023 registered voters from Polimetrix
- 2. Matched sample from an opt-in panel

*** {id: Hypotheses}

- 1. Source label
   - Fox News labeled storues will have higher demand from Republicans and the conservatives
   - CNN and NPR labeled stories will have higher demand from the Democrats
   - Uniform indifference for BBC labeled stories
- 2. Stronger effects of source manipulation for hard news
- 3. Stronger effects of source manipulation for the attentive partisans as opposed to less attentive partisans and nonpartisans

*** {id: Analysis}

- Conditional logit model for discrete choices: utility function depends on attributes of the choices
$$
\begin{aligned}
P_{ij} = \frac{exp(X_{ij}\alpha)}{\sum_{k=1}^{J}exp(X_{ij}\alpha)}
\end{aligned}
$$
- May consider doing this with mixed logit (IIA assumption may be violated)

--- #Results1

## Results
### Overall effects of news labels

>- 1. News source labels are an important cue for readers: consumers tend to ignore stories without labels
>- 2. Fox label has the strongest impact on story selection: its strategy works

--- #Results21

## Results
### Evidence of selective exposure in news selection

```
## Error in readPNG("figure/fig1.png"): unable to open figure/fig1.png
```

```
## Error in rasterGrob(image, x = x, y = y, width = width, height = height, : object 'img' not found
```
#### Figure 1 Effects of story label on story selection

--- #Results22

## Results
### Evidence of selective exposure in news selection
>- 1. Story-level descriptive analysis
   - The effects of labels depend on the subject matters
   - The effects of labels are stronger for the Republicans
>- 2. Individual-level analysis
   - Fox$*$IDE (self-reported political ideology) is positive across almost all subject matters
   - This suggests that Fox label attracted a large number of conservatives
   - Results of Wald tests shows that the differences between Fox and the second-most selected source are significant for conservatives
   - Ideological divide is apparent even for the soft news

--- #Results3

## Results
### Are more involved partisans more selective?
>- 1. Three-way interaction terms: source$*$ IDE $*$PI (political interest)
   - Only the interaction terms for two of the hard news subjects are significant
   - Partial support for the "greater polarization among activists" hypothesis

---

## Conclusion

>- 1. Fox News is the dominant news source for conservatives at the story- and individual- levels
>- 2. Subject matter matters: hard news strengthens selection while exposure to soft news also reveals polarization
>- 3. Implications
   - 1. Polarization among the audience leads to baised news content under the market model
   - 2. Selective exposure may further reinforce existing beliefs and attitudes: the echo chamber effect
   - 3. As the technological advancement further enables customization of the media environment, the effect of selective exposure also grows
   
