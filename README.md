# Analyzing Investments in Startups

## Introduction
A startup is typically referenced to companies in its early stages of operation founded by entrepreneurs developing a product or service to bring to market (Investopedia). Though definitions can vary, its ability to grow, or scale quickly, is considered a key attribute (Robehmed, N.). As a startup goes through the stages of development, investments from both major venture capital firms and individuals who can provide financial support (angel investors) are necessary to help achieve growth. The number of startups has continued to grow over the years but only a few succeed, as a reported 90% of startups fail (Patel, N.). With such a high failure rate, I was curious as to what types of startups investors were funding and if there were any trends among these investments.

## Process
The following steps detail the general process I took in conducting research and analysis on startup investments using Python.

1. I first conducted preliminary research on startup investments in order to familiarize myself with the most common terms and gain a foundational understanding of investing in the realm of startups.

2. I obtained a spreadsheet of Crunchbase’s startup investment data through Kaggle with the goal of analyzing startups by the amount raised to see where investors were putting their money. The data available is from 2014. 

3. I then analyzed my data using Python libraries (Pandas, NumPy, Matplotlib) in a Jupyter notebook.

## Overview of Startup Investing
Investments are made in the early stages of a startup and additional investments are made at several succeeding rounds. Investors are essentially “buying a piece of the company with their investment” in exchange for equity, which entails both partial ownership of the startup and rights to any future profits (Fundersclub). A brief breakdown of the rounds is described below:

- **Pre-seed:** The earliest stage of a startup is usually funded by the founders themselves as it begins operations.

- **Seed:** Considered the “first official equity funding stage” as startups raise money, usually from angel investors.

- **Series A:** Startups demonstrate a track record (determined from key performance metrics such as user base or revenue) and raise money from venture capital firms, usually in the millions.

- **Series B:** Startups go past the development stage and plan for expansion. Venture capital firms continue to invest. Average capital raised is estimated to be around $32 million.

- **Series C:** At this round, startups are considered to be successful and are usually looking for additional funding for new products, to expand into new markets, or to acquire other companies. Hundreds of millions are raised at this point, with hedge funds, investment banks, and private equity firms investing.

## Analysis
Please see my [Jupyter notebook](https://github.com/jks918/portfolio/blob/gh-pages/Startup%20Investments%20-%20FINAL.ipynb) detailing my process.

## Conclusion
The top five companies that raised the most amount of money from investors included some familiar names, such as Uber and Groupon. The top spot was ultimately taken by Clearwire, a telecommunications operator. Although Clearwire ceased operations as of 2015, this suggests that established companies are able to secure more funding as many investment banks, hedge funds, and private equity firms are looking to make “safer” investments rather than take huge risks by funding unknown or smaller startups.

Investors appear to be looking for the next great innovation in critical and promising industries according to the top markets data. Markets such as health care, biotechnology, and clean technology will continue to see investments as it serves an essential need and can impact human lives. Markets like software and e-commerce will also see continued investments as investors are eager to fund the next big startup that will amass millions of users and impact society.

The top types of funding also suggest that investors are more willing to fund startups that have established some sort of track record, as venture capitalists and private equity firms are the types of investors who provided the most funds for these types of startups. However, it is interesting to note that the top funding round did not specify any particular level of funding, indicating that it is the early rounds of pre-seed and seed investments that collectively made up the most amount raised. This aligns with the notion that the majority of startups usually only go through very early stages of investments while major banks and firms will generally only fund a startup that has progressed beyond the seed rounds.

## References
- Robehmed, Natalie. Forbes:
https://www.forbes.com/sites/natalierobehmed/2013/12/16/what-is-a-startup/#5b84b3ce4044

- Fundersclub:
https://fundersclub.com/learn/guides/vc-101/the-risks-and-rewards-of-startup-investing/

- Investopedia:
https://www.investopedia.com/terms/s/startup.asp

- Patel, Neil. Forbes:
https://www.forbes.com/sites/neilpatel/2015/01/16/90-of-startups-will-fail-heres-what-you-need-to-know-about-the-10/#9118da066792
