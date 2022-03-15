# HUH GOVERNANCE

HUH believes that each vote counts, but vote quality and the amount of HUH tokens held for how long count as well. Therefore, HUH Governance is designed to be facilitated by Decentralised Autonomous Organisations (DAOs) using a new consensus strategy whereby vote quality is not compromised, at the expense of increased complexity. It is called ConSenseUs (CSU) – see below.

## HUH DAOs

The default consensus strategy throughout the entire HUH ecosystem is ConSenseUs. HUH DAOs may resort to legacy Plutocracy, Meritocracy, Democracy consensus strategies whenever the community sees fit as a fallback mechanism in order to achieve faster resolutions. The minimum requirement for a HUH DAO to be born is a constitution and an entity presentation article. HUH DAO development kit will support HUH entities (HUH DAOs, users or federations) on the creation of HUH DAO artifacts.

## HUH ConSenseUs (CSU)

HUH entities willing to participate in HUH’s governance should expect that a vote quality assessment will be conducted for most DAO voting processes.

The quality of a vote will be modelled initially as a bi-dimensional feature depending on:

* the consciousness level the voter has on the subject under voting associated with the concerning knowledge fields
* the voter’s frozen stake

The heatmap of the figure 6 shows the vote quality change depending on the consciousness and frozen stake a voter has.

![Fig. 6. Vote quality heatmap](<../../.gitbook/assets/image (1) (1).png>)

A technology based on the [Consider.it](https://consider.it) system is being developed to run our main consensus strategy CSU in order to reach DAOs outcomes. The stake is calculated by the formula in Equation 1.

$$
{ frozenStake = \Delta t_{frozen} * frozenTokensNumber }
$$

​Eq.1 Frozen stake calculation for voting in ConSenseUs strategy.

Where:

* $$\Delta t_{frozen}$$ = time lock period of frozen tokens
* $$frozenTokensNumber$$ = amount of tokens frozen in the token time lock contract.

And vote quality is calculated by the formula in Equation 2.

$$
{ voteQuality = \displaystyle\sum_{n=1} ^{N}frozenStake_{n} * voterConsciousness }
$$

​Eq.2 Vote quality calculation for voting in ConSenseUs strategy.

Where:

* $$voterConsciousness$$ = grade achieved by voter in consciousness assessment on the subject under voting from 0 to 1.
* $$frozenStake_{n}$$ = each $$frozenStake$$ a voter has.
* $$N$$ = maximum number of $$frozenStakes$$ a voter has.

## Freezing

The process of token time locking HUH tokens is called freezing by HUH community. People are incentivised to freeze their stake for longer time and to become more knowledgeable of the most frequent voting subjects as means to increase their voting power.

## HUH Federations

Federated child organizations may form a HUH federation. A HUH federation is any DAO in which at least two different member entities are also a DAO.  The purpose of a HUH federation is to lead around common values among federated entities. The union of federations and organizations is promoted by means of a system designed to reward union tokens to cohesive behaviours. The more behaviours provenly associated with strengthening the union and combating division within the community more HUH union tokens will be granted to the responsible entity.

A strong union observed by HUH entities is analogous to the concept behind a tree where strong roots, trunk and associated branches with 'happy' green leaves are instrumental to achieve sustainable growth.

## HUH Improvement Proposals (HIP)

In [GitHub](https://github.com/HUH-Token), HUH Improvement Proposals (HIP) are to be discussed together with the community by means of pull requests. We are researching the integration of consensus strategies with GitHub through GitHub applications.

***
