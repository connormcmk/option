Option is the fruit of seven years of work to design an economic system that can price externalities. 

Funding from this grant will be used to employ a research lab in characterizing the behavior of Option via direct proof and simulation. In particular, the research lab will focus on the subproblem of judicial selection.

If you’re interested in this project, you might also like to support [Digital Gaia’s Grant](https://gitcoin.co/grants/5468/digital-gaia-high-integrity-impact-certificates-f) (disclaimer, Connor is a team member there, too). Digital Gaia is also working on a credible way to price externalities, starting with climate externalities. We need as many people working on this problem as possible.

---

## What's Option?
Option is a prediction market for governance. Communities that use Option enjoy an environment where it’s profitable for companies to do what’s considered good by the community.

## Why use Option?
**For consumers:**
1. It's easy to choose products that are aligned with personal values and beliefs
2. It's easy to express personal values in a way that will change companies' behavior

**For companies and entrepreneurs:**
1. It's easy to identify which socially responsible action would be beneficial to take
2. It's easy to earn revenue for social goods that would otherwise require grants to support

**For journalists and researchers:**
1. It's easy to be a high integrity researcher or journalist
2. It's easy to find funding for exploring the most important open questions

**For citizens:**
1. It's easy to influence policy in an area of interest
2. It's easy to ignore politics without bad things happening

**For communities:**
1. It's easy to find and form communities of shared values
2. It's easy to make collective choices

## How does Option work?

### Prediction Markets for Policy Setting
Option is a prediction market for governance. [Prediction markets](https://en.wikipedia.org/wiki/Prediction_market) have long been considered an effective way [for groups to make more accurate collective inferences](https://www.science.org/doi/10.1126/science.1157679). The basic way a traditional prediction market works is simple: Anyone can create a market. Like, “It will rain on Thursday.” Then other people can predict the outcome. If the market maker says it rained then the people that predicted YES get paid, otherwise the people that predicted NO get paid. 
Due to the value of accurate predictions, many prediction market platforms have sprung up such as [Augur](https://augur.net/), [Metaculus](https://www.metaculus.com/questions/), [Manifold Markets](https://manifold.markets/home), among many others. Each of these platforms are excellent at aggregating information and incenting accurate predictions, however, they cannot be used for governance. This is because traditional prediction markets suffer from three shortcomings that prevent their usage as governance tools:
1. Moral Hazard — The ability to bet on a particular outcome can create bad incentives. For example,  In 2021 a man bet $50,000 that there would be a streaker at the Super Bowl, then [he put on a leotard and became that streaker](https://www.pokertube.com/article/super-bowl-streaker-bet-50-000-on-himself-but-bovada-won-t-pay-out).
2. Hidden Information — Since earning money is dependent on having special knowledge, betting markets incent proprietary information and insider trading
3. Policy Impotence — Even if a market offers a very accurate prediction, there’s nothing to ensure policymakers will listen to it or interpret it correctly.

**Option circumvents these shortcomings by taking away the opportunity for upside from an accurate trade. In Option, it’s free to be right and expensive to be wrong.** This counterintuitive choice allows Option to redress the shortcomings of prediction markets for use in governance. For example, this design choice solves certain kinds of Moral Hazard: if the man in the leotard had known the best that could happen is he wouldn’t lose $50,000 he never would have put on the leotard in the first place.

**Option automatically sets its policies based on the predictions of the market.** So, when a player predicts they don’t expect to be paid for accurate predictions, instead, Option players make predictions in exchange for shifting the market consensus, and therefore shifting policy. This solves Policy Impotence: predictions in the market directly set policy.

Since Option doesn’t have to pay out for accurate predictions, it can instead use that money to **pay for information that lead to resolution of a prediction**. Standing “resolution bounties” indicate the most high value places where a player can provide information. This solves Hidden Information: players are paid for information.

The details of the mechanisms that power Option are beyond the scope of this grant (if you’re interested you’ll find links at the end). However, it’s worth being familiar with the two general mechanism sets Option uses:
1. the Claim Market
2. the Semantic Market

The Claim Market’s job is to encode beliefs as currency. It gives us:
1. Sincere signaling of belief and values
2. Bribe resistant currency
3. Targeted funding for research and journalism
4. Negative money that’s not debt

The Semantic Market’s job is to instantiate the game for collective inference and policy setting. It relies heavily on the guarantees of the Claim Market. It gives us:
1. A surface to interlock claims (enabling conditional predictions)
2. Increased influence on more testable predictions
3. A way to select unbiased judges for each prediction
4. Game theoretic policy setting

### Setting Policy
Let’s look at a specific example of where regulation was used to try to solve a problem, and how it would have looked different had Option been used. Note that this doesn’t try to tell you why this happens, just describes the behavior.

In 2013 New York City proposed a ban on sugary drinks larger than 16 fluid ounces. The argument by the Board of Health was that the limit would improve public health and make it easier for people to reduce their caloric intake. The argument against this ban was that it would be legal overreach, and it violated the personal autonomy of consumers.

Had New York City citizens been able to use Option, those who wanted to avoid unhealthy drinks would have experienced an increased price for the drinks (akin to a tax) dissuading them from purchasing. In exchange for this tax, Option's prediction that avoiding sugary drinks improves health outcomes would lower the effective healthcare costs of those that opted in to the tax.

As a second order effect of this system, soft drink providers like PepsiCo or CocaCola would find aggregate demand drop for the goods predicted to be unhealthy, incenting them to reduce the health implications of their products.

In this way, **Option maintains individual autonomy while localizing individual responsibility; using markets and preferences instead of legislative bodies.**

### Externalities
But, what about situations where members of a community are harmed by the actions of a company that they don't buy from?

For example, what if a mining operation leaches toxins into a nearby river, which harms a biodiverse ecosystem and degrades the health of locals? If those locals don't purchase products made from the mined minerals they cannot exert influence by boycotting the goods, so it would seem they don’t have market-based ability to minimize the pollution.

Those familiar with economics will recognize that this is a classic example of a negative externality, a “bad thing” that doesn't have a cost associated with it. In this case, the locals and the ecosystem are harmed but the mining operation doesn't pay for that, so they enjoy artificially high profits. The mining company has socialized costs while privatizing gains.

### The Shortcomings of Regulation
One option to solve this problem is regulation. For example, the local government could say, "No more than 0.010 parts per million of arsenic in the water, otherwise we'll fine you 1 million dollars."

However, regulation has some well known problems:
1. Regulation is often slow to respond — markets outpace and outmaneuver the regulators
2. Regulation is often imprecise — it over or under regulates, stifling innovation or permitting great harm
3. Regulation is often non-dynamic — it doesn't update with new knowledge
4. Regulators can become "captured" — the entities they should regulate find ways to influence the decision in their favor

### Coasian Bargaining
Economic theory offers a clever alternative to regulation called, "Coasian Bargaining". The idea is named after Ronald Coase who won the Nobel Prize in Economics for this and related ideas. What would Coase recommend to these people whose river is being polluted?

Unfortunately, his recommendation is very unpalatable to most people. He would tell them to pay the mining operation to pollute less. The mining operation could agree to implement policies to reduce their pollution in exchange for the community paying them to offset the costs of implementing the policies.

However, Coasian Bargaining has proven rarely useful in practice. Even apart from the fact that it feels bad to pay people who pollute, and that it could create a net incentive to pollute more so as to be paid to do less of it, there are more fundamental issues:
1. How can the community know how much it actually costs to reduce pollution?
2. How will the community verify that the company is implementing the policies effectively?
3. How do future generations pay for the benefit of a healthy ecosystem and community?

For example, what if the community is willing to pay 2 million dollars to reduce pollution by 50%, but:
1. The mining company says, "It costs us 5 million dollars to reduce pollution by 50%" when it really only costs them $2 million.
2. It costs 2 million dollars a year to run the water quality tests which confirm the company is complying.
3. Future generations, when asked, say that looking back they would have been willing to pay $50 million for a healthy community and ecosystem, not just $2 million.

Now you can see why Coasian Bargaining is of limited application, it only works where:
1. There's no hidden information about costs.
2. It's easy and cheap to validate performance.
3. The people who are affected are able to pay.

### Option's Coasian Bargaining
How does Option get around this? Option still uses a form of Coasian Bargaining, but rather than pay the mining company to pollute less, **Option allows the local community to put negative valued money into the mining operation’s digital wallet.** This forces the mining company to negotiate with the community. In exchange for this ability, the local community makes predictions (which they stake) that the mining operation can dispute. For example, they might say:
1. “It only costs 1 million dollars to reduce pollution by 50%”
2. “Every year, the mining company leaches 500,000 liters of pollution into the river”
3. “Future generations, when asked, will be willing to pay $100 million for the healthier community and ecosystem they enjoy thanks to the reduction in pollution”

Based on the expected future cost predicted by the local community, Option places a certain amount of negative money into the account of the mining operation.
But what happens if the local community overestimated the size of the future cost? In that case, the mining company can respond with their own predictions, making lower predictions (which they also stake) about the costs of their behavior. For example:
1. “It costs us 3 million dollars to reduce pollution by 50%”
2. “Every year, we only leach 100,000 liters of pollution into the river”
3. “Future generations, when asked, will be willing to pay $10 million for the healthier community and ecosystem they enjoy thanks to the reduction in pollution”

By taking this action, the mining company reduces the amount of negative money Option places in their account. However, this isn't the end of the story. Now all the money that was predicted by the mining company and the local community come into play. That money becomes a bounty which can be paid to researchers and journalists for helping to refine the accuracy of the predictions.

### Disverifier Selection
How do these journalists and researchers get selected and paid? That's one question this grant will fund.

The funds earned from this grant will go toward exploring the exact mechanism for how to select informed, unbiased, and sincere researchers and journalists (or "disverifiers" in Option's parlance). There are three reasons this is a tractable problem:
1. Option offers a natural way to identify bias — a measure of ideological “distance”.
2. Sincerity and accuracy can be well incented by staking mechanisms.
3. Iterative deepening of predictions is a mechanism for incenting precise and resolvable predictions.

Furthermore, this work is worth funding even if optimal disverifier selection proves impossible. It may be possible that the worst case performance of Option is still marginally better than other existing governance processes. For example, we might imagine that Option fails to live up to the standards of the real-world legal system, but offers efficiencies for use in:
1. Governance of Decentralized Autonomous Organizations
2. Open science modeling, e.g. in regenerative agriculture
3. Governance of content moderation on platforms like YouTube, Facebook, and Twitter or their web3 alternatives
4. Replacing bespoke web3 incentive models with API calls to Option, e.g. Sybil resistance for Gitcoin, or decentralized Yelp where each reviewer makes the claim, "This review was left by a real customer who was not paid."
5. DAO certification and open source software funding via predictions like, “This project has no vulnerabilities.” Which simultaneously offers information about the confidence of the developers, while providing bounties for red teaming.

## Use of Funds
This grant will fund three primary activities performed by the [Decision Science and Control (DeSCon) lab](http://cs.uccs.edu/~pbrown2/lab.html) of [Dr. Philip Brown](http://cs.uccs.edu/~pbrown2/) (or his students, depending on the complexity of universities ∪ crypto ):
1. Prove game theoretic properties about the model (or simplified versions)
2. Implement the model in-silico and characterize its behaviors
3. (Stretch Goal) Implement Option as an interactive game

### Questions worth exploring:
* What's the Byzantine Fault Tolerance of the inference model?
* Can we characterize capacity for information aggregation?
* How do wealth effects (e.g. high income inequality) affect system behavior?
* How quickly can a poorly funded accurate predictor overcome a well funded inaccurate incumbent?
* Can Option be framed as a version of a known game for easier analysis, e.g. Beauty Contests?
* What happens if we allow pricing of positive externalities? Does that introduce risks of collusion?
* Is Option capture-proof? How well does Option handle the more general problem of Moral Hazard: companies paying to retain policies that are profitable.
* In what ways might this be exploited to leak private information (e.g. private values and beliefs or transaction history)? Can modifications avoid that?
* Can cognitive biases distort the game theoretic prediction, e.g. paying someone in a dubious claim induces sunk cost bias and doubling down.
* What are the expected psychosocial externalities of using Option? Cf. Twitter and Facebook’s tendency to incite outrage. Look at personas like: intrustors, citizens, disverifiers,
* Given that Option creates funding as a function of disagreement, does this create a meta incentive for disverifiers to stoke disagreement? How does the magnitude of this incentive compare with the existing disagreement incentive of an elected government?

This is an incredibly high level overview of Option and its purpose. If you would like to learn more about the details of the mechanisms that underpin Option, here are some good places to start:
* [Claim Market Prototype (link)](https://coda.io/@connor/claim-market-prototype) This is a toy implementation of the Claim Market, the token layer of Option.
* [Semantic Market Deck (link)](https://drive.google.com/drive/folders/1hr206yCj5DviOgDMG69LAd7m1UP1RDH0) This deck overviews the mechanisms of the Semantic Market, the inference layer of Option.

## Adoption Plausibility
Finally, it's worth addressing the most common objection to Option: if Option makes it more expensive to purchase goods and less profitable to sell goods, and it opens companies up to an additional form of liability, how will it ever get adopted?

For companies, Option fills the same niche as LEED certifications, Better Business Bureau grades, Corporate Social Responsibility teams, and Fair Trade and Organic product labels. For companies that are sincere in their claims, Option creates a measurable surface upon which to demonstrate that sincerity. A company that practices ethical manufacturing will accept Option's currency and stake predictions on Option in order to differentiate themselves from competitors that only purport to practice ethical manufacturing.

Some consumers will reject transacting in non-Option currencies just as some people today refuse to purchase non-Fair Trade goods. Other consumers will transact in Option simply because it can save them money on certain products, e.g. the health insurance savings thanks to the voluntary tax on soda.

Finally, for regulators and lawmakers Option provides new mechanics for making regulations that are responsive to the research community. In the long run, communities, nations, and planets with better foresight and a better ability to avoid negative externalities will outlast those that don't.

---

Exciting, huh? Ready to [go back to Gitcoin and hit that Add to Cart button](https://gitcoin.co/grants/7496/option-governance-for-profitable-goods)?
