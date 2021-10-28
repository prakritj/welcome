## Introduction

Hello! I'm Prakrit Jayakumar, a first year BSc Economics student at the London School of Economics. You have arrived at my Github page, which means you have expressed some interest in me! I'm an international student from Singapore and chose to study Economics because of a passion in Developmental Economics (the 'lottery' of success) and the complex nature of global financial markets. If you'd like to learn more about me, [follow me on Twitter](https://twitter.com/prakritjay).

One of my primary goals during my time at the LSE is to learn how to develop visualisations to comprehend the vast amount of data available on the interweb and apply that to my passion for a more founded understanding of concepts and theories by accompannying it with an analysis of real-world examples which are current and evolving.

|I served my National Service in the military (Singapore Armed Forces) for 2 years from 2019-2021|
|:--:|
|![Image](https://nextcloud.prakritj.com/apps/files_sharing/publicpreview/6x4rHATWZynqCTp?x=3828&y=1508&a=true&file=3f154a6d-9bfb-462c-98fa-f1a6920cf381.png&scalingup=0.png)| 

## Current Project

At the moment, I'm interested in the impact that social media has on global financial markets. Over the past year, reduced consumption spending along with additional government handouts (all due to COVID-19) has meant that workers who kept their jobs had an increased capacity for savings. Much of the recent savings that have flooded the equity market has come from an increase in _active_ retail investing as opposed to _passive_ investing. That is, instead of retail investors pumping more money into stable and renowned indices such as the S&P500, mutual funds, or life insurance which couples as an investment vehicle, retail investors in the equity market  have instead opted to decide for themselves which stocks to invest in. This rise in active retail investing has also been accompanied by a similar rise in social media communities regarding these investment decisions. Most prominent is the Reddit community [r/wallstreetbets](https://reddit.com/r/wallstreetbets). 

r/wallstreetbets has had a tremendous increase in followers over the last year. It gained serious traction during the GameStop saga in January/February 2021, when retail investors gathered on the Reddit community to collectively invest in the company GameStop to force out Wall Street investors, mostly hedge funds, who had aggressively shorted the stock. The saga demonstrated the power of harnessing social media users for collective action.

|Number of Followers (Members) to Reddit community r/wallstreetbets: A rapid increase since 2021|
|:--:| 
|![Image1](https://i.ibb.co/cx5jTqq/newplot.png)|

The collective action has not stopped with GameStop, although it is not nearly to the same scale. The Reddit community discusses potential investment decisions on a daily basis with each other, and these threads garner thousands of comments each day. My goal is to analyse these comments, and by extension the investment decisions that the community on r/wallstreetbets is tending towards.

Each of these comments is given a score based on the number of 'upvotes' and 'downvotes' they get from fellow users. By analysing the contents of each comments, we can derive the stock through the ticker or company  mentioned, as well as the intention to buy or sell.

Of course, data from Reddit has little meaning without context of the equity markets themselves. Therefore, we aim to source data from financial markets on the respective industry, market cap (size of the company), and performance over the the last 3-6 months for each stock mentioned on Reddit.

### Final Product

The final product for this project would be a bubble map. The bubble map would display the stocks listed by Reddit, with circles indicating 'BUY' decisions and squares indicating 'SELL' decisions. Each bubble would be coloured by category; for example, blue for the tech industry, and green for the F&B industry, categorised using data from reputable financial data providers. When hovering over each bubble, one would be able to see details of the stock, including the market cap and performance over time.

One way to achieve this is by implementing a data visualisation tool called D3, which allows us to use Javascript to display bubble charts. A great example of an application of this tool in data science is [this analysis of how the Gates Foundation allocated education spending](http://vallandingham.me/bubble_chart/).

Due to the difficulty in displaying too much information, unpopular investing suggestions/decisions (to be quantified after data is sourced) would be left out of the bubble map, but those wishing to access it will be able to see the data directly. 

## Future Endeavours

In the future, I wish to expand on my current project. One way I can do this is through a more in depth analysis of r/wallstreetbets content; for example, being able to analyse the content of images posted on the community would give me a greater sample of content to analyse. Images would also be an avenue to analysing screenshots, where information such as amount invested and average price of transaction would be accessible. 

It would also be insightful to analyse the **types** of investments that r/wallstreetbets members are inclined on making. From a risk and reward point of view, there is a drastic difference between investing straight into the equity market, and investing in stock options which have the potential to skyrocket as well as tumble. It would be intruiging to determine whether the risk of Reddit investments is significantly higer than other retail investors, or whether the risk-heavy posts are just those that happen to appear more often on social media. An extension of this would be whether social media users potentially influence members towards riskier investments, using text analysis. 

Another potential aspect of this project would be the returns that Redditors realise on their investments. By looking at buy/sell prices, we can derive the average returns and determine whether the r/wallstreetbets community investment strategies do better or worse than passive investment alternatives, such as indices or mutual funds. Going one step further, we can even look into the variance of the returns per user, examining how risk plays a role in the variance of average returns.
