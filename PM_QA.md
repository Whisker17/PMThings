# PM Q&A

- **IF YOU BUILT SOMETHING LIKE THIS, WHAT USE WOULD PEOPLE GET OUT OF IT? MOST PEOPLE/ORGANIZATIONS AREN’T INTERESTED IN IMPROVING THEIR FORECAST ACCURACY THROUGH PMS. WHO WOULD PAY TO CREATE (LET ALONE SUBSIDIZE) THESE MARKETS?**

  Excellent question. Firstly, Authors (who bear the economic cost of Market-Creation) are rewarded with a slice of transaction volume. Recreational speculation is likely in markets covering sports and politics, arbitrage transactions are likely in markets tracking a price index, and in many cases, individuals will just disagree with each other passionately enough to begin wagering (global warming, gun control, etc.).

  Secondly, the [public might just pay for publicly useful information](http://www.themoneyillusion.com/?p=15446).

  Thirdly, although the information revealed by a PM is public, the effect of that revelation may be privately beneficial. For example, consider [Robin Hanson’s Wish](http://www.overcomingbias.com/2008/04/if-i-had-a-mill.html), where conditional PMs are introduced to advise firing an incompetent yet entrenched CEO. With 1000 USD per firm to kickstart this idea, we might then collect data on firm/BoD/investor response. However, if we did not have 1000 USD per firm ourselves (we don’t), is there not someone who would benefit from the creation of this information? Of course there is: the second-in-line for CEO! CEOs are typically paid so much that their salary can be twice that of even the CFO. 1000 bucks is nothing for a decent shot at such a nice raise, to say nothing of the competitive spirit which overwhelms those who seek the top job. Even *better*, individuals would not try this if they suspected their CEO of actually being quite competent. So there is actually an economically-efficient self-selection in the creation of these markets: when unneeded, they are not created. Better still, competent CEOs may themselves create these markets to protect their job (although I doubt this type of activity will happen for some time).

  Fourth, individuals could collaborate via assurance contract to efficiently pool their info-demand. In fact, in [my applications paper](https://github.com/psztorc/Hivemind/raw/master/docs/3_PM_Applications.pdf), I describe a way of using PMs to create extremely incentive-powerful Trustless Dominant Assurance Contracts. To my knowledge nothing similar has ever been conceived.

- **ISN’T THIS JUST GAMBLING?**

  No. Gambling is a game of luck…the return is unalterable by skill. In a casino, the odds do not change, expressing the static uselessness of the betting activity there.

  In a prediction market, the “odds” (the prices) change as a result of information, and as a result of which bets are placed when. The variations in price produce information which is supremely reliable, as well as universally [common](https://en.wikipedia.org/wiki/Common_knowledge_(logic)). This information, produced nearly for free by the voluntary actions of individuals, has tremendous social value.

- **WHAT ABOUT PEOPLE WITH GAMBLING PROBLEMS?**

  Sadly, [around 2% of the population](https://en.wikipedia.org/wiki/Problem_gambling#Prevalence) seem to be unable to control themselves when gambling. This rate [has been stable over time and is independent of casino availability](http://www.americangaming.org/industry-resources/research/fact-sheets/history-problem-gambling-prevalence-rates), suggesting that this is some kind of biological disposition. It is interesting that the DSM-V classifies Problem Gambling under [Substance-Related and Addictive Disorders](http://blog.ncrg.org/blog/2013/05/evolving-definition-pathological-gambling-dsm-5). Similar to alcoholism, [treatments](https://en.wikipedia.org/wiki/Problem_gambling#Treatment) for this unfortunate condition include 12-step programs and CBT.

  The problem of addiction is quite a serious one…it is very difficult to prevent people from doing what they want to do. Even large nation-states, with well-funded law enforcement and court systems, are unable to dissuade many citizens from using drugs. Even when these individuals are *actually incarcerated*, [1 in 50 still can get access to their drugs (in prison)](http://www.washingtonpost.com/blogs/wonkblog/wp/2014/05/13/ron-paul-thinks-drug-use-is-rampant-inside-prisons-hes-wrong/).

  Fortunately, just as individuals can choose to take drugs, they can also choose to join a support group or check themselves into rehab.

  Problem gambling is exacerbated by fast, high payouts at highly improbable odds. PMs don’t offer that at all, as the payouts resemble those of the modern stock market (roughly 1% volatility per *day*). Even far into the future, when Branches mutate into faster “Casino Branches” (should this ever happen), a PM specifically designed to offer some kind of “gambling market” would be, in practice, unable to reliably offer bets at highly improbable odds, as the trades would excessively alter the odds themselves.

  Finally, the market environment does guarantee that these gamblers, at the very least, are always getting fair odds and charged minimal fees.

  And, most finally of all, Bitcoin already enables a great deal of gambling. Hivemind seems unlikely to enable much marginal gambling, let alone marginal problem gambling.

- **IF PMS CAN BE USED TO FINANCE PUBLIC GOODS, CAN THEY ALSO BE USED TO FINANCE PUBLIC BADS (FOR EXAMPLE, TO ASSASSINATE SOMEONE)?**

  This question has grown in popularity to the degree that it warranted inclusion in [the applications paper](https://github.com/psztorc/Hivemind/raw/master/docs/3_PM_Applications.pdf) (Appendix 1, forthcoming).

- **CAN’T PMS BE DRIVEN BY PEOPLE WHO ARE OBLIVIOUS TO HOW LITTLE THEY KNOW?**

  Yes, at first. However, these people will quickly start losing large quantities of money, and thereby lose their ability to influence the market. Moreover, the existence of these ignorant “sheep” will attract “wolves” who profit by correcting the mistakes of the sheep.

- **HOW DO YOU ADDRESS THE PROBLEM OF LOW LIQUIDITY?**

  For PMs which are bounded, it is possible to design them such that traders can always update the market price, by trading with an automated market maker powered by a market scoring rule. http://hanson.gmu.edu/mktscore.pdf I threw together an Excel sheet in the docs folder [LogMSR_Demo.xlsx](https://github.com/psztorc/Hivemind/raw/master/docs/LogMSR_Demo.xlsx) for additional clarification. Feedback is appreciated.

- **WON’T THE BTC/USD RATE BE SO VOLATILE THAT IT OVERWHELMS ANY CHANGE IN THE PREDICTION’S ACCURACY? DOESN’T THIS PROJECT NEED STABLECOINS?**

  This project creates a “stablecoin” for every Decision in it. The Decisions define ‘dimensions’ of the Markets, and partition them into states.

  So it is possible to bet “in” any currency for which there is a Decision (USD, Gold, DJIA, etc.), see [Example 5](http://www.bitcoinhivemind.com/papers/2_PM_Types.pdf).

