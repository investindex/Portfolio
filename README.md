# Building a stock portfolio

Which index funds will produce the most long-term growth? Unsurprisingly, even the most informed investors and researchers do not completely agree. Before proceeding with my recommendation, let me be clear that by proposing a portfolio of multiple funds, I am not suggesting that a more straightforward approach is a bad idea. If daunting complexity might cause you to delay investing, feel free to simplify. Some ways of doing so are described [in the next section](https://github.com/investindex/Funds). Waiting to invest will [cost you a lot more](https://www.youtube.com/watch?v=4gn4F1VmTvM&ab_channel=ThePlainBagel) than not implementing someone’s idea of the perfect portfolio.

Here I will offer advice to US investors for practical implementation of the academic research presented in [this video](https://www.youtube.com/watch?v=jKWbW7Wgm0w&ab_channel=BenFelix). These findings indicate that while investing in a market cap weighted index is a successful approach, diversification in terms of risk factors and geography improves long-term returns as well as the reliability of returns. Certain groups of companies present risks which are somewhat independent from the total market, and deliberately taking these risks carries an expected reward. The first factor is size: small cap stocks tend to outperform large cap stocks. The second factor is value: [value stocks](https://www.investopedia.com/terms/v/valuestock.asp) — whose prices are lower than would be expected based on fundamental metrics like earnings — tend to outperform [growth stocks](https://www.investopedia.com/terms/g/growthstock.asp), which are priced expensively because investors have high expectations for growth of the company's fundamentals. The third factor is [quality](https://www.youtube.com/watch?v=YsWgWrpzdAM&ab_channel=TheRationalReminderPodcast), sometimes called the [profitability](https://www.sciencedirect.com/science/article/abs/pii/S0304405X13000044) factor, because quality is characterized partly by high profitability. As Robert Novy-Marx wrote [here](http://rnm.simon.rochester.edu/research/QDoVI.pdf), "Quality can even be viewed as an alternative implementation of value—buying high quality assets without paying premium prices is just as much value investing as buying average quality assets at a discount. ... Quality and value strategies are highly dissimilar, however, in the stocks that they actually hold. High quality firms tend to be expensive, while value firms tend to be low quality. ... Each of these
strategies consequently tends to do well precisely when the other under-performs, making them exceptionally attractive to run together."

With regard to both domestic and international markets, we can improve long-run stock performance relative to a cap weighted index by targeting these three factors: smaller size, greater value, and greater quality. The effects interact: in particular, the value premium is very strong in small cap stocks. Keep in mind that these premiums are usually but not always positive. 2020 was an especially poor year for value investing, not because returns were negative but because the returns of large cap growth stocks dwarfed those of value stocks.<sup id="fn1">[1](#f1)</sup> Such underperformance for US value had not been seen since 1998 and 1999. Stock market trends are very difficult to predict in the short term, and those who embrace any investing approach need to understand that they will experience periods of underperformance relative to other approaches. How does factor investing fare when stocks plummet? Because correlations are high across the market during crashes, don't expect risk factor diversification to reduce losses. But your portfolio will probably recover more quickly than a cap weighted index, and your returns in good years are expected to be more reliable and usually larger.

An additional approach to indexing can be found in the Research Affiliates Fundamental Index ([RAFI](https://www.researchaffiliates.com/en_us/strategies/rafi.html)). RAFI indices include both value and growth stocks, but weighting of each stock is based on a combination of the company's fundamental metrics, as opposed to its market cap. The result is a value-tilted index, although there are important differences between typical value funds and RAFI funds. They are explained well by the founder of Research Affiliates in [this video](https://www.youtube.com/watch?v=00ZACmAdi7g&ab_channel=TheRationalReminderPodcast). For our purposes here, we will group RAFI funds with value funds.

How can we implement this academic research in a real portfolio? We need to make several decisions about allocation, and precise numbers are always arbitrary to some degree. We can start with our distribution of domestic and foreign stocks. Given the great vigor and size of the US market, I have chosen to allocate 80% to domestic indices and 20% to international indices. An investor purely concerned with global market cap weighting would allocate 55-60% to the US. While geographic diversification may appear to offer some protection against downturns in the US, the actual protection is very limited due to the high correlation between US and international stocks. Although we cannot know if this will always be true in the future, the exceptional historical performance of the US stock market provides some justification for overweighting it. Others may reasonably allocate more to international markets.

Now, how can we invest in the abovementioned factors within the domestic and international markets? It's important to understand that the cap weighted default distributes over 85% of the index weight to large cap stocks, with very little for mid and small cap. But given that small cap value stocks have the strongest historical performance of any category, we should choose to overweight them. I will assign 30% of the total portfolio to US small cap value and 6% to international small cap value. US mid cap value stocks will be overweighted (to a lesser degree) for the same reason, at 20%. Large cap value stocks are expected to outperform large cap stocks and the total market but perform less well than small and mid cap value in the very long term. Large cap value is highly underweighted but still represented to improve the reliability of returns: 10% is assigned to US large cap value and 6% to international large cap value. To complement value, we will assign 20% to US quality and 8% to international quality. The international allocation is far less tilted toward small cap and value stocks than the domestic allocation, partly because of limited fund offerings and partly to prevent any one portion from being too small.

Most markets are not as easily defined as the S&P 500. The total US stock market, for example, has a number of indices which act as a specific definition and performance benchmark. Different index funds that track a given market often use different indices. It is possible for these distinctions to be consequential, as the id="fn1">[footnote](#f1) illustrates, but their influence on future returns can be difficult to anticipate.

Which ETFs and mutual funds can be used to target these indices? My suggestions are organized in tables in the next section, and the webpage for each fund is hyperlinked.

&nbsp;

[Click here for the next section — Fund proposals](https://github.com/investindex/Funds)

&nbsp;

<sup id="f1"> 1 </sup> How painful was 2020 for US value? For each index I will list the total returns by market price for the funds from Vanguard, BlackRock, and Fidelity in that order. The total returns for small cap value were [5.91%](https://investor.vanguard.com/etf/profile/performance/vbr/cumulative-returns), [.72%](https://www.ishares.com/us/products/239588/ishares-morningstar-smallcap-value-etf), and [4.48%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635T773). The total returns for mid cap value were [2.56%](https://investor.vanguard.com/etf/profile/performance/voe/cumulative-returns), [-3.96%](https://www.ishares.com/us/products/239584/ishares-morningstar-midcap-value-etf), and [4.74%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635T799). The total returns for large cap value were [2.29%](https://investor.vanguard.com/etf/profile/performance/vtv/cumulative-returns), [1.55%](https://www.ishares.com/us/products/239715/ishares-core-sp-us-value-etf), and [2.86%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635V679). For US value, 2020 was not great but not terrible. However, the total returns for the cap weighted US market were [21.05%](https://investor.vanguard.com/etf/profile/performance/vti/cumulative-returns), [20.73%](https://www.ishares.com/us/products/239724/ishares-core-sp-total-us-stock-market-etf), and [20.78%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/315911693). This was driven by the success of large cap growth, which had total returns of [40.27%](https://investor.vanguard.com/etf/profile/performance/vug/cumulative-returns), [38.42%](https://www.blackrock.com/us/individual/products/239580/ishares-morningstar-largecap-growth-etf), and [38.43%](https://fundresearch.fidelity.com/mutual-funds/performance-and-risk/31635V729).

US quality funds fared nearly as well as the cap weighted total market: [17.00%](https://investor.vanguard.com/etf/profile/performance/vfqy/cumulative-returns) for Vanguard, [16.97%](https://www.ishares.com/us/products/256101/ishares-msci-usa-quality-factor-etf) for BlackRock, and [16.52%](https://am.jpmorgan.com/us/en/asset-management/adv/products/jpmorgan-us-quality-factor-etf-46641q761#/performance) for J.P. Morgan. [↩](#fn1)
