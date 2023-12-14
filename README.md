# COUNTRY STUDY: JAPAN

Debarshi Goswami, Rehaan Sahay

# **TABLE OF CONTENT**

[**1. INTRODUCTION 3**](#_4a4rxbw3f0l)

[**2. HISTORY 3**](#_uytfsw60ciww)

[**3. GROWTH THEORY 5**](#_pzcib1a7rx22)

[3.1. Growth Model 5](#_umwwrijlsmf8)

[3.2. Calibration 6](#_rbkt3jd233cx)

[**4. ANALYSIS 8**](#_zddd3kbd8dg)

[**5. CONCLUSION 10**](#_561bt6frnxp0)

[**6. REFERENCES 11**](#_kwx38vs9qcv3)

# 1. INTRODUCTION

This study delves into Japan's economic growth through the lenses of Growth Accounting and Deterministic Neoclassical growth calibration. The aim is to examine the factors influencing Japan's economic trajectory systematically. Alongside, we consider the Japanese Asset Bubble burst, not exhaustively, but in relation to our calibrated parameters, seeking connections and implications within our analytical framework.

Throughout this exploration, we aim to contribute to a grounded understanding of Japan's economic evolution. By merging theoretical frameworks with practical insights, we aim to shed light on the dynamics that have shaped Japan's economic journey. Including the Japanese Asset Bubble burst within the context of our calibrated parameters adds a layer of complexity, inviting further inquiry into the interplay between economic models and real-world events.

# 2. HISTORY

Japan, an Island nation located in East Asia, holds a strategic position in the Pacific Ocean, encompassing four main islands—Honshu, Hokkaido, Kyushu, and Shikoku—along with numerous smaller islands. Situated at the crossroads of various maritime routes, Japan's geographic location has historically shaped its cultural and economic interactions.

In the aftermath of World War II, Japan emerged from the devastation as a phoenix, embarking on a remarkable economic resurgence. The post-war period saw the implementation of far-reaching reforms, including the 1947 Constitution, which established a parliamentary democracy, and the U.S.-led occupation's economic restructuring efforts. Japan rapidly transformed from a war-torn nation to an economic powerhouse, marked by a focus on export-led industrialization and technological advancements.

The ensuing decades witnessed unprecedented growth, with Japan's economy often referred to as the "Japanese Miracle." The 1960s and 1970s saw rapid industrialization, characterized by a surge in manufacturing and exports. Innovative approaches, such as the famous Quality Control Circles, bolstered Japan's reputation for producing high-quality goods.

However, this meteoric rise was not without challenges. By the 1980s, Japan experienced the peak of its economic prosperity, marked by the infamous Japanese Asset Bubble. Fueled by speculative real estate and stock market investments, this period saw soaring property and stock prices. The bubble, eventually bursting in the early 1990s, marked a turning point in Japan's economic narrative, leading to a prolonged period of economic stagnation known as the "Lost Decade."

The historical trajectory of Japan, from post-war recovery to the zenith of economic success and subsequent challenges, sets the stage for a nuanced examination of its growth journey through the lenses of Growth Accounting and Deterministic Neoclassical growth calibration.

# 3. GROWTH THEORY

To analyse the Japanse crisis in 1992, we collected macroeconomic data for Japan for the period 1980 to 2019. Japan faced economic challenges post-bubble burst, with a declining stock market and deflation, we try to document these changes in policies with the help of data and our growth models.

## 3.1. Growth Model

The aggregate production function we assume is a Cobb-Douglas function,

,

Where Y is the aggregate output, is TFP, K is the aggregate fixed capital used in production, and L is the work-eligible population.

By looking at the capital and labour growth rate, we can account for TFP in output growth. Using our data, we find that during the asset bubble burst in 1992, labour growth fell and TFP fell. And primary growth during this period was caused by the growth in capital. Over the following decades, Japan's labour force continued to declined, but the TFP rose, showing that Japan began becoming more efficient.

| Period | Output Growth | Factors |
| --- | --- | --- |
| Capital Growth | Labour Growth | TFP Factor |
| --- | --- | --- |
| 1980 - 1992 | 3.80% | 1.69% | 0.46% | 1.66% |
| --- | --- | --- | --- | --- |
| 1992 - 2000 | 0.97% | 0.99% | -0.02% | -0.01% |
| 2000 - 2010 | 0.58% | 0.34% | -0.31% | 0.55% |
| 2010 - 2019 | 0.88% | 0.17% | -0.49% | 1.20% |

Table 1: Growth Accounting

For the data, we mainly used OECD as our prime resource. Though we also used some Time Series tables from FRED for data on compensation for labour as an overall part of GDP and found data on indirect tax from IMF. The data itself may have inconsistent assumptions.

## 3.2. Calibration

For our calibration, we formulate the Social Planner's Problem,

![](RackMultipart20231214-1-i99zwo_html_7365e568769337f2.png) ,

Subject to the constraints,

![](RackMultipart20231214-1-i99zwo_html_e0238c1829a9a8de.png)

![](RackMultipart20231214-1-i99zwo_html_a1897c7cb5b65d1b.png)

After writing this in terms of our effective variables, we get the following maximisation problem

![](RackMultipart20231214-1-i99zwo_html_dfab19418a3f4568.png)

Subject to constraints,

![](RackMultipart20231214-1-i99zwo_html_e8affab4ba59400d.png)

![](RackMultipart20231214-1-i99zwo_html_a1897c7cb5b65d1b.png)

We have estimated the parameters of our constraints using data from 1980 to 2019, to analyse the effect of the Japanese asset price bubble using our model. The model has five parameters: 𝜂 denotes the population growth rate, 𝛾 is the improvement in labour productivity, 𝛩 is the total factor of productivity, 𝛿 is depreciation and 𝛽 is the discount factor. The values we estimated for each parameter is given in Table 2.

| **Period** | **α** | **β** | **γ** | **δ** | **η** | **r** | **θ** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Whole | 0.41 | 0.9497 | 1.0201 | 0.0414 | -0.0011 | 0.091 | 380.6434 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1980 - 1992 | 0.3855 | 0.9434 | 1.0299 | 0.036 | 0.01 | 0.1 | 399.5426 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1992 - 2000 | 0.395 | 0.9533 | 1.0109 | 0.0408 | 0 | 0.09 | 417.9553 |
| 2000 - 2010 | 0.4253 | 0.9531 | 1.0119 | 0.0449 | -0.01 | 0.09 | 326.4854 |
| 2010 - 2019 | 0.426 | 0.9554 | 1.0187 | 0.0462 | -0.01 | 0.09 | 377.4017 |

TABLE 2: Calibration

# 4. ANALYSIS

# ![](RackMultipart20231214-1-i99zwo_html_6234e81e24e66226.png)

#


r-𝛿 is the real return to capital. As we can see from the above mapping the returns to capital increased from 1984 till 1991 before crashing down and not ever recovering to it's value. We interpret real return to capital as returns from assets (stocks and real estate) and thus use this to map asset value.

The primary characteristic of the bubble is the rapid increase in asset prices. First, the stock prices began to increase rapidly. It peaked at the end of 1989, priced at 38,915 JPY (3.1 times what it was in 1985 during the Plaza Accord). In August 1992, the index fell sharply to 14,309. Real estate prices also increased, with a time lag. This price rise spread from Tokyo to Osaka, Nagoya, and other cities. The Urban Land Price Index reached a peak in September 1990 (4 times that in September 1985). Land prices declined thereafter. Land prices in 1999 were on average 20 percent lower than even in 1985.

In the long run we see a downward trend of returns to capital and this represents Japan's "lost decades", which was a failure of Japan to economically recover in the post period of the bubble burst even as of late 2010s.

![](RackMultipart20231214-1-i99zwo_html_8dcf1950806be625.png)

Output growth has a sharp decline at the time of the crisis, and seems to be recovering two decades after it occurred. During the crisis, a majority of the output growth was due to the capital growth (from Table 1). The output growth rate has been highest (above 4%) before the crisis, and Japan has struggled to recover for the past 3 decades, which are now commonly known as the lost decades for Japan.

# 5. CONCLUSION

We have attemped to explain the asset price bubble and the lost decades using calibration and growth accounting even when we have good picture of Japan's growth (or lack thereof) we cannot quite capture the factors behind the bubble and the lost decades only relying on this. An extension to this paper could be accounting Japan's central bank monetary policy and the foreign exchange.

#


# 6. REFERENCES

- Hayashi, Fumio, and Edward C. Prescott. 2002. "The 1990s in Japan: A Lost Decade." _Review of Economic Dynamics_ 5, no. 1 (January): 206 - 235. https://doi.org/10.1006/redy.2001.0149.
- Kehoe, Timothy J. 2021. "Computation." Timothy J. Kehoe. https://users.econ.umn.edu/~tkehoe/computation.html.
- University of Groningen and University of California, Davis, Capital Stock at Constant National Prices for Japan [RKNANPJPA666NRUG], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/RKNANPJPA666NRUG, November 29, 2023.
- OECD (2023), Net national income (indicator). doi: 10.1787/af9be38a-en (Accessed on 29 November 2023)
- OECD (2023), Gross national income (indicator). doi: 10.1787/8a36773a-en (Accessed on 29 November 2023)
- OECD (2023), Investment (GFCF) (indicator). doi: 10.1787/b6793677-en (Accessed on 29 November 2023)
- University of Groningen and University of California, Davis, Real GDP at Constant National Prices for Japan [RGDPNAJPA666NRUG], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/RGDPNAJPA666NRUG, November 28, 2023.
- World Bank, Population, Total for Japan [POPTOTJPA647NWDB], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/POPTOTJPA647NWDB, November 28, 2023.
- https://www.theatlantic.com/magazine/archive/2013/05/the-slacker-trap/309285/
- Okina, Kunio. "The Asset Price Bubble and Monetary Policy: Japan's Experience in the Late 1980s and the Lessons." MONETARY AND ECONOMIC STUDIES /FEBRUARY 2001, vol. (SPECIAL EDITION), 2001. Bank of Japan, [https://www.imes.boj.or.jp/research/papers/english/me19-s1-14.pdf](https://www.imes.boj.or.jp/research/papers/english/me19-s1-14.pdf).