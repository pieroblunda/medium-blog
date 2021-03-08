# Is IE a business in 2020?

Piero Blunda | 5 min read | [View on medium](https://pieroblunda.medium.com/is-ie-a-business-in-2020-26ea96684dbd)

Historically, Internet Explorer (IE) was the unique way to use Internet in the 90s and the early of 2000. Even [Apple used it as a default browser](https://en.wikipedia.org/wiki/Internet_Explorer_for_Mac_OS_X) before they launch Safari. Since Google launch Chrome, users start migrating from IE to Chrome, a better, modern and faster browser powered by Google.

The question is: __How convenient is to develop an IE software compatible today?__ Let’s read some stats to answer better.

## Currently scenario

Currently, 52% of total internet users prefer browsing the web using their mobile phones. This is more than desktop users (44%). Today, there is not any version of IE for mobile devices.

Sept.2019 | Mobile | Desktop | Tablet
---- | ---- | ---- | ----
Shared | 54% | 43% | 3%

Sept-2019 | All platforms | Desktop
---- | ---- | ----
Worldwide | 1.41% | 3.26%
Europe | 1.38% | 2.70%
North America | 2.24% | 5%
South America | 0.37% | 0% 

## Thinking business oriented: the cost of IE

Any investor think: __“What do I spend my money on?”__. Suppose we have a company with an e-commerce that works only in Google Chrome that earns u$d 1M/year. It means that that company has invested 100k (suppose an investment of 100k) in order 1M of revenue (100%) coming from Google Chrome users. It sounds as a good business for the investor.

Making the same example a bit complex, the e-commerce could add IE support and it will carry on a cost associated. Company continues with an income of u$d 1M yearly. The investor continues asking __“What do I spend my money on?”__. The company’s budget is still 10%, so the 100k must be divided. So, the questions are: How many money I am spending in this technology? What is the associated ROI? How long does the business last?

|    | Market Shared | Outcoming (10%) |  Incoming |
|:------|-------------:|---------------:|---------:|
| IE     | 1.41%         | 1.4k            | u$d 1.4k  |
| Others | 98.59%        | 98.6k           | u$d 98.6k |

Table above shows us a very simply simulation of investment. In this way a company must to 1.41% (so 1.5%) of budget in a programmer IE oriented in order to follow the good-sense budget. In addition, these number are visitor, not customers. People who buy using IE can be less because conversion rates are correlated with the user experience.

Websites at the scale of Amazon, for example, may generate __tens of millions of dollars from IE users__, even if they represent less than 1% of total traffic. This is to considerate if you are owner of a digital product as big as them. In anyway, large companies like Youtube (from Google) or Github (from Microsoft) removed IE support recetly, but is not a real situation for the 99.9% of digital products.

In addition, supporting a IE generates inevitably a Technical debt. Many code and 3rd-party libraries must be added to support IE causing slowly-programming in the present and a rework in the future to fix the technical debt.

## Question #1: How many money I am spending in this technology?

You should to trace the effort spent by developing for IE. The magic number is 1.5%. If your effort is higher than 1.5%, it means that developing for IE is not self-sustain and it is financed by other product. This is common practice when talking about products with a strong growth projection. Table below show you the calculated 1.5% of commons unit measures.

| Unit time | Timeboxing (1.5%) |
|:----------|:------------------|
| 1 hour    | 1 minutes         |
| 1 day     | 7 minutes         |
| 1 week    | 30 minutes        |
| 1 month   | 3 hours           |
| 1 year    | 4 days            |

If you are spending more time than indicated in the table above, you are definitely reducing ROI. Use [timeboxing](https://en.wikipedia.org/wiki/Timeboxing) in order to be inside the budget and better time management.

## Question #2: What is the associated ROI?

As a Product Owner you should to know the ROI of each feature of your product, including work in IE. The table below shows how is modified the ROI by changing the invests (time spent) in a feature. For example, if you should to spend 15 minutes, but your really spend 1 hour, you are overflow by 4x and your ROI decrease by 75%. The numbers may change depending on the ROI and the type of business. The digital magazine css-tricks wrote an excelent article detailing how affect the IE support to your general product quality and other aspect like productivity and conversion rate.

|  Unit time  |       ROI       |
|-----------:|---------------:|
| 1x          | 1               |
| 2x          | -50%            |
| 3x          | -67%            |
| 4x          | -75%            |
| 5x          | -80%            |
| 6x          | -83%            |
| 7x          | -86%            |
| 8x          | -88%            |
| 9x          | -89%            |
| 10x         | -90%            |

In economics words, this is a typical case of the law of [diminishing returns](https://en.wikipedia.org/wiki/Diminishing_returns). The effort to develop to IE increase considerably and the benefit produced by the output is insignificant.

![Graph 1](https://miro.medium.com/max/1400/1*VcMLuIEKrQqBoMllDkb8yA.jpeg)

## Question #3: How long does the business last?

Nobody invests in a declining market. So, as investor it have not sense to spend money in a technology like Internet Explorer because it is not scalable. The following graph shows the trend of the IE users market.

![Graph 2](https://miro.medium.com/max/1400/1*4kQxZ0GxsOUgQ1E9uf7y3g.png)

## How to resolve it?

Usually people collect requirements as a list, and simply ask to the customer __“Should it work in Internet Explorer?”__. Stop for a moment and think that your client is not an IT expert and does not know the costs associated with the software development process. Can you imagine the answer? Of course! He would say “Yes! (Happy face)”.

Instead, show him the above information first and ask “Do you want to invest in this market or do you prefer to maximize the conversions of the majority market? Try to convince him to not to develop for IE showing valid arguments in order to highlight that both are in the same team and the team is business focused. If the client insists on the importance of the internet explorer, ask him what his arguments are and try to understand them. Maybe you will discover something new.

You should to negotiate it with the customer or Product Owner. Use this card if you consider it. Do not allow the customer manage the risk. It is ok if you have to say “no” to the customer. Remember your goal is to carry the project forward. If you identify IE as a threats (it mean can be causes delay in your project planning), avoid to take the risk. You can also defer develop IE-support in order to prioritize other tasks.

I found a few cases where it would be necessary to support the Internet explorer. One of them may be the dependency of the plugins (like ActiveX) used in IE. In general, they are very mature banking systems that have a very high update cost associated with them. The other example is that of companies where 0.5% of users represent millions of people. For example, the most visited site in the world is YouTube with 1.6 Billion monthly visits and 0.5% of them equals 81M people who watch advertising and generate income.

Examples above even make little sense in 2020. YouTube and many others big companies like Spotify and Atlassian stopped support to IE. Microsoft Edge and mobile Apps are replacing that old banking systems.

## Reference
* [Platform market share](https://gs.statcounter.com/platform-market-share/desktop-mobile-tablet)
* [A business case for dropping internet explorer](https://css-tricks.com/a-business-case-for-dropping-internet-explorer/)
* [Timeboxing - Wikipedia](https://en.wikipedia.org/wiki/Timeboxing)
* [What is ROI?](https://www.workana.com/i/glossary/what-is-roi/)
* [Diminishing returns - Wikipedia](https://en.wikipedia.org/wiki/Diminishing_returns)