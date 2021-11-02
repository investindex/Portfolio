# Building a stock portfolio

Which funds will produce the most long-term growth? Unsurprisingly, even the most informed investors and researchers do not completely agree. Before proceeding with my recommendation, let me be clear that by proposing a portfolio of multiple funds, I am not suggesting that a more straightforward approach is a bad idea. If daunting complexity might cause you to delay investing, feel free to simplify. Some ways of doing so are described [in the next section](https://github.com/investindex/Fund/blob/main/README.md). Waiting to invest will [cost you a lot more](https://www.youtube.com/watch?v=4gn4F1VmTvM&ab_channel=ThePlainBagel) than not implementing someone’s idea of the perfect portfolio.

We should start with background on portfolio characteristics. With regard to market cap, a company can be large cap (>$10B), mid cap ($2B to $10B), or small cap (<$2B). The total US market [distributes](https://www.morningstar.com/etfs/arcx/vti/portfolio) about 72% to large cap, 20% to mid cap, and 8% to small/micro cap. Of course there are many small cap companies, but the sum of their market value is a small fraction of the market value of all publicly listed US companies. A cap-weighted total US index fund closely mirrors this market cap distribution.

Stocks can be characterized on a spectrum of relative price, where the halves of the spectrum are called value and growth. Value stocks have _lower_ share prices than would be expected based on [fundamental](https://www.investopedia.com/terms/f/fundamentalanalysis.asp) metrics like earnings. In contrast, growth stocks have _higher_ share prices than fundamentals would suggest. So relative price expresses whether a stock has a high or low price compared to the price one would expect based on its fundamentals. In general, growth stocks have expensive prices relative to current fundamentals because investors have high expectations for growth of the company. Value and growth are not dichotomous descriptors. As an analogy, someone may be described as extraverted or introverted, but the trait extraversion is a continuous dimension. So there are important differences between two extraverts who score at the 70th and 99th percentiles of extraversion, respectively; and some people around the 50th percentile are not especially introverted or extraverted. Because a cap-weighted total US index fund mixes growth and value stocks, it is characterized as a _large blend_ fund (where _large_ refers to the dominance of large cap stocks).

One division among foreign markets is important to understand. There are _developed markets_ outside the US, led in size by Japan, the UK, Canada, France, Switzerland, Germany, and Australia. Then there are _emerging markets_, led by China, Taiwan, India, Brazil, South Africa, Saudi Arabia, Russia, Thailand, and Mexico. South Korea is usually but not always grouped with developed markets. When some people say _international markets_, they mean developed markets, while others are referring to all foreign markets. If I am referring only to developed or emerging countries, I will specify, and otherwise _international_ refers to markets outside the US.

Cap-weighted funds that invest in the total US or global market are simple, great options for many reasons.<sup id="fn1">[1](#f1)</sup> However, those willing to add moderate complexity to their portfolios can improve their expected returns.

&nbsp;

## Moving beyond market cap weighting

Here I will offer advice to US investors for practical implementation of the academic research presented in [this video](https://www.youtube.com/watch?v=jKWbW7Wgm0w&ab_channel=BenFelix). These findings indicate that while investing in a cap-weighted index fund is a successful approach, diversification in terms of risk factors and geography improves long-term returns as well as the reliability of returns. Not all stocks carry the same expected return — a _risk factor_ refers to a characteristic which accounts for systematic differences in the risk and returns of diversified stock portfolios. Deliberately taking the risks associated with certain categories of stocks carries a greater expected reward. [Risk factors](https://www.youtube.com/watch?v=Val9CqkqmvM&ab_channel=TheRationalReminderPodcast) influence the returns of bonds as well, but those factors are more obvious. As we discussed [earlier](https://github.com/investindex/Risk#understanding-bonds-and-their-risks), they are _term_ and _credit_. Longer-term bonds have greater expected returns than shorter-term bonds, and bonds with higher credit risk have greater expected returns than those with lower credit risk. So term and credit are risk factors for bonds; what are the risk factors for stocks?

The first factor is simply the market factor: a cap-weighted stock market index tends to outperform the risk-free rate of return (the return on the lowest-risk assets like one-month US treasury bonds). A standard cap-weighted index fund has exposure to only the market factor. The second factor is [size](https://www.youtube.com/watch?v=uErHwq4M6pg&ab_channel=BenFelix): small cap stocks tend to outperform large cap stocks. The third factor is [value](https://www.youtube.com/watch?v=2MVSsVi1_e4&ab_channel=BenFelix): value stocks tend to [outperform](https://www.youtube.com/watch?v=kYO7xrHhqsY&ab_channel=BenFelix) growth stocks. The fourth factor is [profitability](https://www.youtube.com/watch?v=YsWgWrpzdAM&ab_channel=TheRationalReminderPodcast): stocks with robust profitability tend to outperform stocks with weak profitability. And the fifth factor is investment: stocks with conservative investment into growth of company assets tend to outperform those with aggressive investment. The stocks which tend to outperform, like value stocks, deliver a higher expected return because of their greater risk.

For a longer explanation of what factors are at a beginner level, see [this podcast](https://www.youtube.com/watch?v=CJ6Mrrbvxzg&t=1468s&ab_channel=TheRationalReminderPodcast) in which Ben Felix explains factors to his mom. For a more advanced explanation, see [this footnote](https://github.com/investindex/Fund/blob/main/README.md#f2) in the next section. It will help resolve questions caused by a superficial understanding of factors, such as: how could more profitable stocks be riskier?

We've established that we can improve long-run stock performance relative to a cap-weighted index by targeting these factors: size,<sup id="fn2">[2](#f2)</sup> value, profitability, and investment. But while the premiums are positive in the long run, they are sometimes reversed on shorter time scales. Factor-tilted portfolios cannot provide constant outperformance, because their higher returns are the result of a different risk profile. That risk must entail underperformance during some periods, or it wouldn't actually be risk. 2020 was an especially poor year for value investing, not because returns were negative but because the returns of large cap growth stocks dwarfed those of value stocks.<sup id="fn3">[3](#f3)</sup> Stock market trends are very difficult to predict in the short term, and those who embrace _any_ investing approach need to understand that they will experience periods of underperformance relative to other approaches. Naturally, radical outperformance is also possible. For US value this occurred in 2000 after the tech bubble popped.<sup id="fn4">[4](#f4)</sup>

A recent period from 2017-2020, in which US value stocks have been beaten handily by US large cap growth stocks, has caused many people to question the value premium. There will always be people who think trends in the last five or ten years upturn everything we know about investing. But we can observe data on the impressive historical consistency of factor premiums, and find that someone with a long time horizon is very likely to reap the risk premiums of these factors. In rolling 10-year periods [from 1963 to 2020](https://www.pwlcapital.com/wp-content/uploads/2020/12/Five-Factor-Investing-with-ETFs.pdf#page=16), value stocks beat growth stocks 86% of the time, stocks with robust profitability beat stocks with weak profitability 86% of the time, and stocks with conservative investment beat those with aggressive investment 98% of the time. All three of these premiums were positive in 100% of rolling 20-year periods. The cap-weighted market beat risk-free returns in only 80% of 10-year periods, although we can rest assured that it also reached 100% consistency in 20-year periods. So the value, profitability, and investment premiums have been more consistent than the market premium! These are US data, but the factors are [persistent](https://www.pwlcapital.com/wp-content/uploads/2020/12/Five-Factor-Investing-with-ETFs.pdf#page=16) in other countries as well.

Optional knowledge: An additional approach to indexing can be found in the Research Affiliates Fundamental Index ([RAFI](https://www.researchaffiliates.com/en_us/strategies/rafi.html)). RAFI indices include both value and growth stocks, but weighting of each stock is based on a combination of the company's fundamental metrics, as opposed to its market cap. The result is a value-tilted index, although there are important differences between typical value funds and RAFI funds. They are explained well by the founder of Research Affiliates in [this video](https://www.youtube.com/watch?v=00ZACmAdi7g&ab_channel=TheRationalReminderPodcast).

Let's sing praises of diversification for a moment.

&nbsp;

## Clarifying diversification

Increasing _risk-adjusted return_ is one of the central goals of rational investing. If someone changes a portfolio to achieve higher return while keeping volatility constant, or to reduce volatility while keeping return constant, they have increased the risk-adjusted return. Diversification is the main mechanism for doing so. In particular, investing in assets that have low or moderate correlations with one another enhances the risk-adjusted return of the overall portfolio. Ideally, diversified assets will succeed and fail at somewhat different times, making routine volatility as well as the largest crashes more tolerable.

Recall the [section on rebalancing](https://github.com/investindex/Risk#rebalancing--risk-maintenance), where I focused on the importance of maintaining your intended allocation of stocks and bonds. We'll explore another way in which disciplined rebalancing helps you, in combination with diversification. Let's start with an [example](https://www.youtube.com/watch?v=RR7e1Y-HJxQ&t=315s&ab_channel=BenFelix): between January 1970 and June 2009, in Canadian dollars, the S&P 500 had an average annual return of 9.66%, a Canadian index returned 9.42%, and an international index excluding the US and Canada returned 9.28%. Superficially, you might think that this means an investor would've received the highest return by investing in the S&P 500 and ignoring the other two. But a periodically rebalanced portfolio with one-third allocated to each index returned 9.84%, a higher return than any of the funds with lower volatility than any of the funds! Over a period as long as four decades, these differences are more significant than they may seem.<sup id="fn5">[5](#f5)</sup>

So diversification among stock funds and rebalancing can provide your portfolio with higher returns than any of its constituents. This exact result does not usually occur, but the example illustrates the advantages of this approach. Rebalancing into the funds that have recently underperformed is a counterintuitive but effective practice. And with a forward-looking perspective, we don't know which countries or sectors will perform best at which times, so we take a fairly agnostic approach. This is consistent with the assumption that markets are [efficient](https://www.youtube.com/watch?v=rbPVTqd468c&ab_channel=BenFelix) enough to make it very difficult to select stocks in advance that will outperform the market without accepting a higher level of risk.

From a defensive point of view, lack of diversification threatens your financial well-being. The financial advisor Larry Swedroe often tells the story of a retired couple he met in March 2003 on a book tour.<sup id="fn6">[6](#f6)</sup> Three years earlier they had been invested in a concentrated portfolio of growth stocks. They were chasing the extraordinary recent returns of tech stocks enabled by the internet, and when the tech bubble burst in 2000, they took it on the chin. Their retirement portfolio was reduced from $13 million to $3 million. This is an extreme example, but not an anomaly. These are the kind of real financial consequences to which you make yourself vulnerable if you concentrate your portfolio in a small number of similar stocks and fail to diversify broadly across the market. See, for instance, how the stock prices of [Cisco](https://finance.yahoo.com/quote/CSCO) and [Qualcomm](https://finance.yahoo.com/quote/QCOM) behaved in 2000 and imagine buying shares as they approached their peaks.

#### Risk factor diversification

Some of the factor funds, like small cap value, will exhibit higher volatility than the cap-weighted total market. But this doesn't imply that factor investing delivers a more volatile portfolio. In other words, although factor investing involves overweighting riskier stocks, it is not necessarily a riskier approach. To the contrary, investing in a variety of funds that are not perfectly correlated means that each risk factor acts as a somewhat independent source of returns, and those returns tend to deliver at different times. Losses or stagnation in one fund may be accompanied by gains in another.

A prominent [example](https://www.portfoliovisualizer.com/backtest-asset-class-allocation) is the entire decade of 2000-2009, in which the total US market and [S&P 500](https://www.ssga.com/us/en/individual/etfs/funds/spdr-sp-500-etf-trust-spy) had negative average annual returns (-0.27% and -1.01%, respectively). It is often called the _lost decade_ because stock returns in the US were so poor. But it was not lost for value stocks: Vanguard's large cap value fund returned an average annual 1.23% and their small cap value fund returned an average 7.69%. The 2000s also illustrated the value of geographic diversification: Vanguard's emerging markets fund returned an average 9.82%. Many naive investors, who base all of their investment knowledge on the last decade and think the S&P 500 can do no wrong, should peer a little further back in history.

Even when the movement of different risk factors is the same directionally, one fund may gain more or lose less than another. The smoother returns of a portfolio with multiple risk factors are thanks to the free lunch of diversification.

How does factor investing fare when stocks plummet? Because correlations are high across the market during major crashes, don't count on risk factor diversification to reduce losses in percentage terms. But your portfolio will probably recover more quickly than a cap-weighted index, and your returns in good years are expected to be larger and more reliable.

See this section's [last footnote](https://github.com/investindex/Portfolio#f7) for more on geographic diversification.

&nbsp;

## Implementation

How can we apply these ideas to a real portfolio? First we can consider geographic allocation. An investor purely concerned with global market cap weighting would allocate [about](https://www.msci.com/acwi) [59%](https://www.ftserussell.com/products/indices/geisac) to the US, 31% to other developed markets, and 10% to emerging markets. Many investors have a home country bias, and US investors in particular think they have justification for their chauvinism given the great domestic returns since 2012. But a large home country bias [is not sensible](https://github.com/investindex/Risk#f1) regardless of where you live, and there are good reasons to avoid allocating 100% to the US market or any other country's market.<sup id="fn7">[7](#f7)</sup> I recommend 50-65% allocation to the US.

We should, however, depart from global cap weights by overweighting subsets of the market with positive long-term premiums. These are stocks with low relative price (value stocks) and high profitability. As discussed in [this footnote](https://github.com/investindex/Portfolio#f2), size may not be an important risk factor on its own. But because some factor premiums are stronger _within_ small cap stocks, we should overweight small cap value stocks, especially those with high profitability. These stocks arguably have the highest expected return of any category.

This may cause some people to wonder why it isn't advisable to invest _only_ in small cap value stocks. There is indeed a strong case that great returns would be expected for someone with this portfolio if they had a time horizon of at least 20 years and an iron will. But over the course of those 20+ years, there would undoubtedly be periods of significant [underperformance](https://github.com/investindex/Portfolio#f3) compared to a more typical portfolio, like a cap-weighted global fund. For most people, these periods would be so psychologically punishing that it's doubtful they would be able to avoid changing their allocation or bailing out of stocks altogether. For augmented returns that are more reliable, we should invest in globally diversified stocks across all market capitalizations and with different relative price and profitability characteristics. We can overweight some stocks without reaching the extreme of omitting the underweighted stocks. The reliability of our returns will be the gift of risk factor diversification and geographic diversification.

In the next section, the term _quality_ will be used for certain factor-tilted funds. Quality, in its most rigorous definition, arguably ought to [refer](https://www.researchaffiliates.com/content/dam/ra/documents/faj-second-quarter-2019-what-is-quality.pdf) to the profitability and investment factors. However, it is mainly a [marketing term](https://www.youtube.com/watch?v=YsWgWrpzdAM&t=1143s&ab_channel=TheRationalReminderPodcast) for funds that select stocks based on a variety of "healthy balance sheet" indicators. Strategies under the quality label can differ substantially. Some are better than others at efficiently targeting the profitability and investment factors, which are the variables that systematically account for differences in risk and return.

Which ETFs and mutual funds can be used to build a portfolio with these characteristics? Various suggestions are organized in tables in the next section, and the webpage for each fund is hyperlinked.

&nbsp;

[Click here for the next section — Fund proposals](https://github.com/investindex/Fund/blob/main/README.md)

&nbsp;

All sections:

* [Cover page](https://github.com/investindex/Intro)
* [Introduction to index funds](https://github.com/investindex/Index)
* [Thinking about risk](https://github.com/investindex/Risk)
* [Your psychology](https://github.com/investindex/Psychology)
* [Guidelines for financial planning](https://github.com/investindex/Guidelines)
* [Building a stock portfolio](https://github.com/investindex/Portfolio)
* [Fund proposals](https://github.com/investindex/Fund/blob/main/README.md)
* [Concerns for the small investor](https://github.com/investindex/Small)
* [Concerns for the large investor](https://github.com/investindex/Large)
* [Practical information for execution](https://github.com/investindex/Practical)
* [Taxes](https://github.com/investindex/Taxes)
* [Vocabulary and further resources](https://github.com/investindex/Vocab)

&nbsp;

Footnotes:

<sup id="f1"> 1 </sup> Total market index funds have a lot going for them. First, because stock returns are [highly](https://www.youtube.com/watch?v=xfdMDGIABek&ab_channel=BenFelix) [skewed](https://www.youtube.com/watch?v=thNrIsU88y8&ab_channel=BenFelix) — a small fraction of stocks drive the market's growth — a poorly diversified investor is more likely to randomly underperform than randomly overperform. Total market index funds provide the broad diversification needed to capture skewed returns. Second, management fees are low because their holdings are based on straightforward rules. Third, they have low turnover, which implies chiefly long-term holdings, leading to tax efficiency and lower explicit trading costs such as the [bid-ask spread](https://www.investopedia.com/terms/b/bid-askspread.asp).

Fourth, investing according to market cap weight means funds are distributed in proportion to the available opportunity set. This has several advantages. It means most trades occur with large cap stocks, which are highly liquid and have minimal trading costs. It maximizes the strategy's capacity. Capacity for any investment approach would be reached if everyone piled on the same strategy, eliminating the risk premium after costs. Because a total market index fund distributes assets according to the opportunity set, reaching capacity is not a concern. The strategy's capacity is vast. Moreover, the predominance of large cap stocks lowers [implicit](https://www.tandfonline.com/doi/pdf/10.1080/0015198X.2019.1567190) [trading costs](https://github.com/investindex/Portfolio/blob/main/MarketImpactTrading.pdf). Buying shares puts upward pressure on the price, and selling exerts downward pressure. This is because, if you are selling shares (for example), the number of people willing to buy from you at a given price is limited, and after exhausting those offers, you must move your sell price lower in order to keep selling. Trading many shares thus causes meaningful price movement in a way that costs the trader. Stocks with larger market caps are less susceptible to the implicit cost of price movement, because any given trade taps a smaller fraction of the available liquidity. [↩](#fn1)

&nbsp;

<sup id="f2"> 2 </sup> The existence of a small cap premium is far more doubtful than I have portrayed it until here. For evidence, see [this video](https://www.youtube.com/watch?v=uErHwq4M6pg&ab_channel=BenFelix) and [these](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-the-Size-Effect) [papers](https://github.com/investindex/Portfolio/blob/main/SettlingTheSizeMatter.pdf). The practical implication is that you should not invest in small cap funds with the expectation of higher returns. However, some factor premiums are stronger _within_ small cap stocks. The value premium is strong among small cap stocks, weaker among mid cap stocks and still weaker among large cap stocks. As [this paper](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-Value-Investing) points out, the Fama-French value factor expresses the premium of investing in value vs. growth in a portfolio split evenly between small cap and large cap. Small cap carries the team. If market cap weighting were used, large cap would dominate, and the Fama-French value premium wouldn't be statistically significant in most samples. So what's the conclusion? While you should avoid pure small cap funds, it still makes sense to overweight small cap stocks, but only the small cap stocks such as those in value funds.

The first paper linked above on the size factor is from authors at AQR Capital. For the interested reader, they have also written papers on the [value](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-Value-Investing) and [momentum](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-Momentum-Investing) factors, the latter of which is not part of the Fama-French [five-factor model](https://www.sciencedirect.com/science/article/abs/pii/S0304405X14002323) discussed above. The AQR papers are accessibly written and provide a window into some of the disagreements surrounding risk factors. [↩](#fn2)

&nbsp;

<sup id="f3"> 3 </sup> How painful was 2020 for US value? For each index I will list the total returns by market price for the funds from Vanguard, BlackRock, and Fidelity in that order. The total returns for small cap value were [2.84%](https://investor.vanguard.com/etf/profile/performance/viov/cumulative-returns), [2.56%](https://www.ishares.com/us/products/239775/ishares-sp-smallcap-600-value-etf), and [4.48%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635T773). The total returns for mid cap value were [2.56%](https://investor.vanguard.com/etf/profile/performance/voe/cumulative-returns), [3.53%](https://www.ishares.com/us/products/239764/ishares-sp-midcap-400-value-etf), and [4.74%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635T799). The total returns for large cap value were [2.29%](https://investor.vanguard.com/etf/profile/performance/vtv/cumulative-returns), [1.55%](https://www.ishares.com/us/products/239715/ishares-core-sp-us-value-etf), and [2.86%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635V679). For US value, 2020 was not great but not terrible. However, the total returns for the cap-weighted US market were [21.05%](https://investor.vanguard.com/etf/profile/performance/vti/cumulative-returns), [20.73%](https://www.ishares.com/us/products/239724/ishares-core-sp-total-us-stock-market-etf), and [20.78%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/315911693). This was driven by the success of large cap growth, which had total returns of [40.27%](https://investor.vanguard.com/etf/profile/performance/vug/cumulative-returns), [38.42%](https://www.blackrock.com/us/individual/products/239580/ishares-morningstar-largecap-growth-etf), and [38.43%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635V729). [↩](#fn3)

&nbsp;

<sup id="f4"> 4 </sup> How good was 2000 for US value? We'll use [data](https://www.portfoliovisualizer.com/backtest-asset-class-allocation) from Vanguard's mutual funds that were in operation at the time. Large cap growth (VIGRX) returned -22.21% and the total US market (VTSMX) returned -10.57%. But large cap value (VIVAX) returned 6.09% and small cap value (VISVX) returned 21.88%. [↩](#fn4)

&nbsp;

<sup id="f5"> 5 </sup> Imagine an initial investment of $10,000, invested in the ways I described above. Over 39.5 years, a 9.28% average annual return would yield a final value of $332,900; a 9.42% return would yield $350,200; a 9.66% return would yield $381,900; and a 9.84% return would yield $407,400. For example, $10,000 × 1.0984^39.5 = $407,418. [↩](#fn5)

&nbsp;

<sup id="f6"> 6 </sup> See chapter 3 of Larry Swedroe's book, co-authored with Kevin Grogan, [_Your Complete Guide to a Successful and Secure Retirement_](https://libgen.is/search.php?req=Swedroe+Grogan+Your+Complete+Guide+to+a+Successful+and+Secure+Retirement&open=0&res=25&view=simple&phrase=1&column=def). [↩](#fn6)

&nbsp;

<sup id="f7"> 7 </sup> A common argument one hears is that geographic diversification can offer some protection against downturns in the US. It would be nice if the stock markets of different countries crashed independently of one another, so a globally diversified portfolio would have a smooth ride upward. But different stock markets are [positively correlated](https://personal.vanguard.com/pdf/ISGGEB_042021_Online.pdf#page=6), and this is most true during crashes. Don't expect geographic diversification to act as a cushion during crashes.

There are many ways to argue more convincingly for geographic diversification. The first is to note that there are country-specific risks. The US may experience unexpectedly high inflation. This would cause lenders to anticipate further high inflation and raise interest rates. The US stock market would then suffer because rising interest rates mean companies pay more to borrow money, reducing their expected growth. Inflation is sometimes caused by factors that do not affect all countries equally, so diversification offers mild protection against inflation risk, one example of a country-specific risk.

This [video on bear markets](https://www.youtube.com/watch?v=Jh9Gn58r9Fw&ab_channel=BenFelix) from Ben Felix is a great discussion of the psychological terror of market crashes. It also contains a powerful argument for diversification based on the Japanese stock market. Japan's market grew at a breathtaking pace in the 1970s and 1980s, then crashed in 1990 and has since performed very poorly. From 1990 onward, a Japanese investor with a portfolio of 100% Japanese stocks would have deeply regretted their lack of diversification. But someone who allocated 45% to Japan according to global cap weights at the time would have benefited from superior growth in other countries like the US. As [this paper](https://www.aqr.com/Insights/Research/Journal-Article/International-Diversification-Works-Eventually) put it, "Diversification protects investors against the adverse effects of holding concentrated positions in countries with poor long-term economic performance. Let us not fail to appreciate the benefits of this protection." Ben Felix also points out that Japanese small cap value stocks have outperformed the total market, which supports risk factor diversification. I am not claiming that the US stock market is likely to stagnate; I am saying that the future is uncertain and diversification provides moderate protection from certain risks without any clear drawbacks.

I expand more on the errors of US home country bias in [this footnote](https://github.com/investindex/Risk#f1) to the risk section. [↩](#fn7)

&nbsp;

<!--
Note for author in case of dead links. "Quality, in its most rigorous definition, arguably ought to [refer](https://www.researchaffiliates.com/content/dam/ra/documents/faj-second-quarter-2019-what-is-quality.pdf) to the profitability and investment factors." Link leads to the paper "What is quality?" by Hsu, Kalesnik, and Kose (2019). "Moreover, the predominance of large cap stocks lowers [implicit](https://www.tandfonline.com/doi/pdf/10.1080/0015198X.2019.1567190) [trading costs](https://github.com/investindex/Portfolio/blob/main/MarketImpactTrading.pdf)." Links lead to the papers "Transaction costs of factor-investing strategies" by Li, Chow, Pickard, and Garg (2019) and "The market impact of passive trading" by Aked and Moroz (2015). The latter paper was published [here](https://jot.pm-research.com/content/10/3/5.full), and I included a PDF in this repository because it is paywalled. "For evidence, see [this video](https://www.youtube.com/watch?v=uErHwq4M6pg&ab_channel=BenFelix) and [these](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-the-Size-Effect) [papers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3686583)." Links lead to "Fact, fiction, and the size effect" by Alquist, Israel, and Moskowitz (2018) and "Settling the size matter" by Blitz and Hanauer (2020). The latter paper was published [here](https://jpm.pm-research.com/content/47/2/99), and I included a PDF in this repository because it is paywalled. "For the interested reader, they have also written papers on the [value](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-Value-Investing) and [momentum](https://www.aqr.com/Insights/Research/Journal-Article/Fact-Fiction-and-Momentum-Investing) factors, the latter of which is not part of the Fama-French [five-factor model](https://www.sciencedirect.com/science/article/abs/pii/S0304405X14002323) discussed above." Links lead to the papers "Fact, fiction and value investing" by Asness et al. (2015); "Fact, fiction and momentum investing" by Asness et al. (2014); and "A five-factor asset pricing model" by Fama and French (2015). "But different stock markets are [positively correlated](https://personal.vanguard.com/pdf/ISGGEB_042021_Online.pdf#page=6), and this is most true during crashes." Link leads to page 6 of Vanguard's 2021 paper "Global equity investing: The benefits of diversification and sizing your allocation". This paper has been updated multiple times, so the link may break when they update it. "As [this paper](https://www.aqr.com/Insights/Research/Journal-Article/International-Diversification-Works-Eventually) put it ..." Link leads to "International diversification works (eventually)" by Asness, Israelov, and Liew (2011).
-->
