+++
title = 'Dating, Gale–Shapley, Optimal stopping and Poisson'
date = 2025-08-17T14:32:06+08:00
+++

Often we wonder who to date: Will they be my life partner? Why is dating so hard in our 20s and 30s? The short answer is there's no perfect matching for everyone on both sides, but most people don't exactly understand their preferences anyways.

## [Gale–Shapley's Stable Matching Problem](https://en.wikipedia.org/wiki/Gale–Shapley_algorithm) as a Null Model

Gale–Shapley's Stable Matching Problem serves as a reasonable null model with the most generic assumptions on the population (the large majority I'd be addressing). Firstly, assumes two same-sized sets of binary gender each oriented towards the opposite gender and each individual knows exactly their preference ranking of the opposite gender in a discrete sense, maximal self information. For simplicity we write M and F as these binary gender sets.

### Implications in Dating
We often site the fundamental result is that it shows that a stable matching exists such cheating will never be two-way consensual (any pair of non M-F couples will prefer each other at the sametime). 

Perhaps a more fundamental implication for life can be studied in the way the optimal solution was constructed. The proposing side given enough time to propose will reach an optimality of their preferences and always reach the same stable matching regardless of the order of proposal (one which is best for all proposers and worst for all proposées). Hence at scale it'd mean that if proposers could keep on proposing and pairs can keep changing no one by pretending to propose to one of the opposite gender then the other to game, and also the process with terminate finitely every time with the same matching.

Assuming that people at minimum new what they liked and wanted the best outcome for them, those with high agency would find the partner of their higher preferences rather than if they were passive perhaps to the effect of the worst stable outcome for the passive.

Perhaps this is why:

1) Dating apps like to say "We've found that being the most 'yourself' on your dating profile" leads to the best outcomes.

2) Don't play-games has a fundamental mathematical grounding. Exploiting information asymmetry in games are don't work as well if the person you're pairing with has access to other options (elasticity of dating apps).

3) You should be confident to swipe right and not just wait on those who find you even if you think you're lucky.

4) But also there could just be no perfect matching even if they knew everything in dating apps so get swiping and stop blaming them, they're just tools increase your self-optimizing market efficiency.


### Other Implications 

Some other thoughts I had about life:

1) In Meta's internal research they found it optimal that being accurate in their open positions led to more optimal self-selecting outcomes.

2) People with self adjancency often find themselves in better places in society.

3) Emotional Intelligence, self consciousness, knowing yourself and exactly what you want leads to more optimal outcomes.

4) For consumer niche companies such as platforms, it's important that they have a single business model serving a single side: Meta, Google are all B2B. Focus on a niche 

## Poisson

Ok perhaps the null model above is a large simplification of the process of matching. Most of the time it seems that we're throwing darts into the wild when dating in our 20s, especially after university or with online dating. We often tell ourselves I've been out with countless of dates and why have I not found the one for me, will I be get married in my mid 30s or 40s or even ever? We'd say "dating is just a numbers game."

When we see statistics like oh you're expected to be married by around X because it says it in some online [statistics](https://en.wikipedia.org/wiki/List_of_countries_by_age_at_first_marriage), but more often an overarching societal narrative and fuzzy sense of your mid 20s to mid 30s seems reasonably the average based on your parents. We often dread if were on the far side of the statistics, and frantically try to date as much as possible or feel hopeless after Y amount of dates.

Admittedly, there is emotional exhaustion in the mix. But sometimes I can't help to think that time sampling or using count and blaming it for misfortune or determination of success. And honestly, I'd beg to differ. Unless Tinder, Hinge, Bumble etc... whatever dating app is out to get you and the dates you meet all know each other and are conspiring against you and the world is so, each person you meet is "almost surely" (yay for my measure theory friends) independent of one another. Think of the different people you've dated, especially if you feel as if you're one of the unlucky ones, each time the person didn't know the last and their feelings only depend on their current state and you.

## Implications in Dating

With the assumption independence of each date from each other, we'll bring this back to a crude approximation of Poisson, that in fact perhaps we should look at time X or count Y of dates which define our current success or future. Perhaps we should look at it with some self agency. That Poisson is parameterized by a variable lambda the rate, perhaps the rate at which we put ourselves out there to meet the next person who could be the one, each time we should at least learn from our past experiences, but since the next person is a stranger to your last, treat it with memoryless expectations. And this brings us back to self agency of lambda, which we can determine to make ourselves a target for luck.

### Other thoughts with Poisson

1) Perhaps the same can be seen with consistent hard work beating talent

2) Paul Graham also talks about consistently exploring, being curious, and trying makes us a target for luck in [How to Do Great Work](https://paulgraham.com/greatwork.html)

3) Same applies everywhere in sports, music, research, career advancement, self improvement etc.

## Optimal Stopping

In construction.