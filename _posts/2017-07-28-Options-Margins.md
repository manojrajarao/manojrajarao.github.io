---
layout: post
title: "Options Margins Simplified"
excerpt: "Overview of How Options Margins are calculated"
tags: [Margins, Margin Calculation, Spreads, Iron Condors, Investing, Strategies, Options, Calls, Puts, Vertical Spreads, Greeks, ]
comments: true
toc: true
---

# What are Options Margins?<a id="sec-1" name="sec-1"></a>

Options Margin is the amount of cash a trader is required to deposit into account as a collateral before selling options. The amount required varies based on the type of options transactions. When a trader makes an opening trader on an exchange, the exchange may require the trader to deposit with the clearing house some amount of *margin* or *good faith capital*. Such deposits ensure that if the market moves adversely, the trader will still be able to fulfull any future financial obligations resulting from the trade.

# Who provides the guidance for the amount of margins?<a id="sec-2" name="sec-2"></a>

Margin requirements are provided by Federal Reserve Board. However, the broker may choose to enforce some additional margin requirements on the accounts. Brokers require investors to provide margin funds for when they need to buy or sell underlying stocks. They may also be needed to close losing positions.

# How are margins determined for options?<a id="sec-3" name="sec-3"></a>

Margin requirements are not applicable to all options transactions. Some Option strategies don't have any margin requirements. Ex: Covered Calls, Covered Puts, Long Calls, Long Puts. Margin requirements for both options and underlying contracts are set by the clearning house, using current value of the position as well as the potential risk. While an underlying position, particularly, if it's a futures contract, usually has a fixed margin requirement, the margin for an option contract can change over time since the margin for an option often depends on the amount by which it is in- or out-of-the-money. Positions consisting of a combination of different options or options and underlying instruments may have lower margin requirements depending on the amount of cash required for future settlements. As mentioned before, the idea behind margins is to ensure that the investor has suffcient capital to initiate and hold positions for as long as desired.

Here's an example of Margins calculation for Credit Call Spread:

    Short (Credit) Call Spread
    
    Difference between the short strike price and the long strike price x number of contracts
    
    (premium received from the sale of the call(s) may be applied to meet the initial margin requirement)
    
    Example:
    
    Sell to open 8 contracts Mar 47 Call at 1.00
    
    Buy to open 8 contracts Mar 55 Call at .05
    
    8 x 8 x 100 = $6,400

Here's an example of Margins calculation for Credit Put Spread:

    Short (Credit) Put Spread
    
    Difference between the short strike price and the long strike price x number of contracts
    
    (premium received from the sale of the put(s) may be applied to meet the initial margin requirement)
    
    Example:
    
    Sell to open 7 contracts Apr 43 Put at 1.25
    
    Buy to open 7 contracts Apr 38 Put at .40
    
    5 x 7 x 100 = $3,500

An an example for Short Iron Condors:

    Short Iron Condor
    
    The short (credit) spread requirement for only one side of the strategy.
    
    (Premium received from the sale of the short call(s) and put(s)) may be applied to meet the initial margin requirement)
    
    Example:
    
    Buy to open 7 contracts Apr 52 Call at .80
    
    Sell to open 7 contracts Apr 47 Call at 2.50
    
    Sell to open 7 contracts Apr 43 Put at 1.25
    
    Buy to open 7 contracts Apr 38 Put at .40
    
    5 x 7 x 100 = $3,500

An example for Short Calendar Spreads:

    Short Time Spread: Equity Options
    
    Difference between the short strike price and the long strike price x number of contracts
    
    The short option must expire before the long option
    
    (premium received from the sale of the short put(s) or call(s) may be applied to meet the initial margin requirement)
    
    Example:
    
    Sell to open 5 contracts Feb 43 Put at .85
    Buy to open 5 contracts Jun 40 Put at 1.40
    3 x 5 x 100 = $1,500