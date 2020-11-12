---
layout: post
title: Simultaneous multiple round auctions and the 2020 Nobel prize
---

In this post, I will explore what revolutionary new auction format led to the [Nobel Prize in Economic sciences](https://www.nobelprize.org/nomination/economic-sciences/) in 2020 being awarded to [Paul Milgrom](https://www.nobelprize.org/prizes/economic-sciences/2020/milgrom/facts/) and [Robert Wilson](https://www.nobelprize.org/prizes/economic-sciences/2020/wilson/facts/), two professors at Stanford University.

In 1994, two years before [William Vickrey](https://www.nobelprize.org/prizes/economic-sciences/1996/vickrey/facts/) won his Nobel [prize](https://www.nobelprize.org/prizes/economic-sciences/1996/summary/) in auction theory, the [United States Federal Communications Commission](https://www.fcc.gov/auctions/about-auctions), (FCC for short) had a big problem. If it wanted to use traditional auctions to sell all of its telecommunication frequency slots, this would either lead to giving away the licenses for free or ending up with a telecom monopoly in the United States. So, they asked three brilliant young economists for help who then came up with a solution that was so ingenious, that two of them (Paul Milgrom & Robert Wilson) would win the Nobel prize for it in 2020.

*If you prefer to consume this story in video format, check it out here:*

<iframe width="560" height="315" src="https://www.youtube.com/embed/7ORxtyVq0DE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### The goals

Before the economists got to work on how to best sell the telecom frequency licenses, the FCC told them that it had two goals of which the first was by far the most important. Its main goal was that there should be an efficient telecommunications market. This means that citizens have a good service for a decent prize. Second, the FCC indicated that, while the first goal was the most important, it hoped to get a good price for the telecom frequency licenses because the revenue from the sale would benefit the taxpayer in the end.

Now, before we move on to how these frequencies were sold, let’s quickly review exactly what was for sale.

### What makes the telecommunication frequency license market such a difficult market

Telecommunication frequencies are also known as radio frequencies, radio spectrum or radio waves. Radio waves are transmitted via antenna’s that reach a certain geographical area. There are different wave lengths for different types of purposes. For example, some wave frequencies are used for radio broadcasting, while others are used for television broadcasting, or for mobile phones.  

From an economic perspective, it is advantageous to own several of these frequencies at the same time, both for different areas, such as States in the United States, as well as for different wave frequencies. This means that the value of holding one license depends on whether you hold another license. For example, holding the mobile phone wave length for Nevada might be worth 20 Million dollars on its own. But, if you hold the same license for California, the Nevada license will be worth 40 Million. And if you happen to also own the television frequency for Nevada, the mobile phone wave length license might be worth even more, because this allows you to sell them as a package deal to customers.

### The problem with auctions

This complexity is exactly why this problem was so hard for auction theorists. As mentioned in my last [post](http://www.moneymacro.rocks/2020-10-28-auction-theory-1/) on auctions, standard auctions such as the English, Dutch, and Vickrey auction are very efficient if you want to sell individual objects. However, they are not great at selling multiple related objects all at once.

Say that all licenses are sold, roughly, at the same time and you want to buy the Nevada mobile phone license. You know that you can make 20 million if you are able buy it, on its own, 40 million if you also get the California license, 25 Million if you get the television licence for Nevada, and 50 million if you are able to secure them all. However, you are not bidding for the licenses as a package, you are bidding for them individually. So, you don’t know if you will win the others if you win one.

What makes this problem even more complicated is that while these are the packages that might work well for your company, your competitors have different packaging needs. For example, they might not need the television frequency for their packaging because they have no expertise in tv broadcasting. But, they might like to package the mobile phone license with a radio license instead. This makes it really difficult to predict what your competitors are going to bid on these licenses and thus very tricky to guess if you will be able to get the combination that suits you. Therefore, it makes sense that you don’t bid much higher than the 20 million that it is worth on its own to avoid a big loss if you cannot get the right combination. And since everyone will be under-bidding like this, the proceeds from these individual auctions will likely be very low for the government.

Now, one obvious alternative would be to just sell the license in packages. But, it is extremely difficult to calculate exactly how to package the licenses since the best combination is different for every company. One option that then remains is to sell all of the licenses in one package to a big company. But, then this company will be a monopoly and this is what the FCC told the economists that it did not want.

### The previous solution: beauty contests

To solve these problems, before 1994, the government had sold these licenses via so-called *beauty contests*.

Like in a real beauty contest, potential companies that want to buy frequencies will need to show that they are –the most beautiful candidate- or the best candidate, to do so. At the start of a beauty contest the government publishes a list of criteria such as having good coverage, excellent service, and low prices. Firms will then tell the government which package they want and what they are going to do with these license. Then, the government would award the packaged licenses to the parties that, according to their judgement, made the most beautiful pitch.  

As you might imagine, there are some major problems with beauty contest. Are government bureaucrats really able to determine who will be the best provider based on a pitch alone? What makes this even more difficult is that these companies could easily pretend to be better than they really are. Thus, there are many opportunities for favouritism and even corruption.

It is thus not surprising that the revenue collected by beauty contest was typically very low and the service was often bad as well because the licenses did not always go to the companies that could best use them, but rather to those companies who had the best relationship with the government.

### Summary of the problem

So, that was the full problem for our Nobel Prize winners to be. They needed to come up with an auction format which would **(1) not result in a monopoly** and **(2) in which potential buyers would be able to obtain the right combination of frequencies to suit their needs**. To facilitate that, the auction should signal to buyers what their competitors need to a certain extent, so that companies know which frequency combination can be obtained for a reasonable price and which are a lost cause because other bidders want them so badly. If they learn about this during the auction, this might help them switch their bids to a more realistic combination of frequencies.   

### The solution that the Nobel Prize winners came up with

The solution that Milgrom and Wilson won the Nobel prize for, is now known as the [Simultaneous Multiple Round Auction](https://www.cambridge.org/core/books/market-design/simultaneous-multiround-auction-format/68C91F82D152A6A9995852AFA7FEB966). This auction is very similar to the well-known English auction that is often used to sell art. This means that the participants in the auction will start bidding low, and submit rising bids during the auction. Also, the participant with the highest bid will win the auction and buy the frequency at the price of his or her highest bid.

There are however some aspects that are unique to the Simultaneous Multiple Round Auction and they are both right there in the name. The first unique aspect is that this auction is simultaneously taking place for multiple frequencies. The second difference is that the bidding happens over multiple rounds so that buyers can indeed learn a bit about the preferences of their competitors so that they can update their strategy accordingly.

In the Simultaneous Multiple Round Auction, every round works like this. Any bidder can bid on any number of items. Each round there is a set period of time in which these potential buyers can submit their bids. All bidders will either have kept at least a highest bid in place or post a new bid every round, otherwise they are excluded from bidding in later rounds. At the end of each round, it is revealed to all who is currently winning for each frequency along with the prices of the highest bids.

A next round is then started in which people have the opportunity to raise the current highest bid for each item. The auction stops if no new bids are placed in a new round and then each bidder will receive the frequency for which they currently have the highest active bid. The bidder will pay the price of their highest bid for each item.

For example, say that there is a simultaneous multiple round auction in your country for one radio, two mobile phone, and one 4g frequency. Say there are three phone companies that are interested and that it is especially interesting for them to at least own 1 mobile phone license combined with either a 4g or a radio license. Furthermore, company one has a strong preference for the radio license because it serves mainly elderly customers, company two on the other hand prefers the 4g license for its younger customer base, and company three likes any of these combinations and would even profit the most from having all three unique licenses.  

When the first auction round starts, there will be simultaneous bidding for all four licenses. Let’s say that all companies submit bids on all four licenses and that company 1 has the highest bid for the radio frequency, company 2 has the highest bid for 4g frequency, and company 3 has the highest bid for both the mobile phone frequency.

Since all companies have placed bids, the auction will proceed to a second round, with all companies still participating. Now here something important has happened and that is that all companies now have additional information based on these bids. That is, it is starting to show that company 1 really wants the radio frequency, and company 2 really wants the 4g frequency. The bid of company 3 on the mobile phone frequency is less telling because all companies need the phone license to make their other license more worthwhile.

Now just, to keep this example simple. Suppose that this is enough information for the first two companies to realise that they are not really bidding against each other. Furthermore, the third company might now realise it will be difficult to win against its more specialist competitors and it will stop bidding as a result. Now, in the second round company 1 will keep its bid on the radio frequency, company 2 in the 4g frequency, and they both will place highest bids for each mobile phone license respectively.

Since there was still bidding, a third round will start, but here no new bids will be placed. In the end the first two companies will be in the market. Compare this to an auction where all licenses would have been sold at once. In that case the end result would have likely been a monopoly for the third company.

Now, I hope you agree that the Simultaneous Multiple Round Auction sounds like a smart solution in theory. But, now the real question is … did it work in practice?


### Conclusion

The answer is a resounding yes! The auction created a competitive market by assigning thousands of licenses to hundreds of companies and raised plenty of money in the process. In fact, the 1994 FCC auctions raised some [$20 billion US dollars](https://www.nobelprize.org/uploads/2020/09/advanced-economicsciencesprize2020.pdf). This was twice the forecasted amount. It was so successful that the Simultaneous Multiple Round Auction format became the dominant design for radio frequency sales worldwide, continuing to make governments such of those of [Germany](https://de.wikipedia.org/wiki/Versteigerung_der_UMTS-Lizenzen_in_Deutschland), [India](https://en.wikipedia.org/wiki/Indian_Telecom_Spectrum_Auction), and Spain billions in revenue.

You can see that it makes sense that Milgrom and Wilson just won the Nobel prise in economic sciences for their work.

### What is next?
However, it might surprise you that the Nobel prise in economic sciences is often not considered a ‘real Nobel prise.’ To find out why stay tuned for the next and final post in this mini-series on the Nobel prise in economic sciences. Or, check out my previous [post](http://www.moneymacro.rocks/2020-10-28-auction-theory-1/) on the 1996 Nobel prise on auction theory or start a discussion in the comment section.
