# Harmonic Trading Patterns
The Fibonacci sequence is one of the most famous formulas in mathematics because it is observed throughout nature.  Each number in the sequence is the sum of the two numbers that precede it.  So, the sequence goes: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, and so on.  After the eighth sequence of calculations, there are constant mathematical ratio relationships that can be derived from the series.  Starting with the sum of the eighth calculation (34) as the numerator and using the sum of the ninth equation (55) as the denominator, the result yields 0.618.  In the inverse calculation of these numbers, the same rules apply and the calculation yields 1.618.  Interestingly enough, this study can be applied to financial markets in the form of ratios (i.e., 0.618 and 1.618) derived from the Fibonacci sequence.  Harmonic trading is an area of technical analysis that utilizes the powerful synergies of Fibonacci measurement techniques to quantify specific price patterns.

In the Universe...

<img src="images/Screen Shot 2022-01-10 at 6.40.54 PM.png" width="520" height="350">

In Financial Markets...

<img src="images/Screen Shot 2022-01-10 at 6.47.02 PM.png" width="340" height="210">

The primary goal of this project is to provide a harmonic trading function that can distinguish all points within a 5-point price structure given each Fibonacci calculation that corresponds with a specific harmonic pattern.

## Using Harmonic Trading Patterns
Harmonic trading patterns are comprised of five points: X, A, B, C, and D. In this function, the user must supply the X point (the starting price of the pattern), the A point (the ending price of the first move in the pattern), the XAB ratio (the percentage of the B point relative to points X and A), the ABC ratio (the percentage of the C point relative to points A and B), the BCD ratio (the percentage of the D point relative to points B and C), the XAD ratio (the percentage of the D point relative to points X and A), and the AB=CD ratio (the percentage of the D point relative to points A and B). The output is a five point harmonic trading pattern, or five points in currency terms, and a potential reversal zone (PRZ) which encompasses D, XAD, and ABCD, as well as three take profits: 38.2%, 61.8%, 100% and one stop loss: 38.2% (generated using the measurement from the A point to the D point). A corresponding visualization has been added to allow for the observation of all of the above mentioned more clearly.

So in the example we have below, there is a theoretical asset with a starting price of 1460 (represented by X) and then it makes a move up to 1520 (represented by A).  If we wanted to see what the rest of the prices would be at B, C, and D according to a "perfect bat pattern" we would plug in the values of 0.5 (represented by XAB), 0.618 (represented by ABC), 2.0 (represented by BCD), 0.886 (represented by XAD), and 1.27 (represented by ABCD).  All of these parameters would return what is seen below, and if all of the price levels were touched in the "potential reversal zone" then perhaps this could signal a buy.

<img src="images/Screen Shot 2022-01-10 at 6.48.08 PM.png" width="810" height="480">

## Risk Disclosure
Gregory DeSantis is not a registered broker, analyst, investment advisor or anything of that sort.  This project is purely for guidance, informational and educational purposes.  All information contained herein should be independently verified and confirmed.  I do not accept any liability for any loss or damage whatsoever caused in reliance upon such information or services.  Please be aware of the risks involved with any trading done in any financial market.  Do not trade with money that you cannot afford to lose.  When in doubt, you should consult a qualified financial advisor before making any investment decisions.

## Disclaimer
Trading and investing in any asset involves substantial risk of loss and is not suitable for every investor.  The valuation of any asset and futures may fluctuate, and, as a result, you may lose more than your original investment.  The highly leveraged nature of futures trading means that small market movements will have a great impact on your trading account and this can work against you, leading to large losses or can work for you, leading to large gains.

If the market moves against you, you may sustain a total loss greater than the amount you deposited into your account.  You are responsible for all the risks and financial resources you use and for the chosen trading system.  You should not engage in trading unless you fully understand the nature of the transactions you are entering into and the extent of your exposure to loss.  If you do not fully understand these risks you must seek independent advice from your financial advisor.

All trading strategies are used at your own risk.

Any content in this project should not be relied upon as advice or construed as providing recommendations of any kind.  It is your responsibility to confirm and decide which trades to make.  Trade only with risk capital; that is, trade with money that, if lost, will not adversely impact your lifestyle and your ability to meet your financial obligations.  Past results are no indication of future performance.  In no event should the content of this correspondence be construed as an express or implied promise or guarantee.

Gregory DeSantis is not responsible for any losses incurred as a result of using any of our trading strategies.  Loss-limiting strategies such as stop loss orders may not be effective because market conditions or technological issues may make it impossible to execute such orders.  Information provided in this correspondence is intended solely for informational purposes and is obtained from sources believed to be reliable. Information is in no way guaranteed.  No guarantee of any kind is implied or possible where projections of future conditions are attempted.

None of the content published in this project constitutes a recommendation for any particular asset, portfolio of assets, transaction or investment strategy is suitable for any specific person.  None of the information providers or their affiliates will advise you personally concerning the nature, potential, value or suitability of any particular asset, portfolio of assets, transaction, investment strategy or other matter.

The content provided in this project is solely for educational purposes.  The generic market recommendations provided are based solely on my personal judgment and should be considered as such.  You acknowledge that you enter into any transactions relying on your own judgment.  Any market recommendations provided are generic only and may or may not be consistent with the market positions or intentions of myself.  Any opinions, news, research, analyses, prices, or other information contained in this project are provided as general market commentary, and do not constitute an investment advice.

CFTC RULE 4.41 – HYPOTHETICAL OR SIMULATED PERFORMANCE RESULTS HAVE CERTAIN LIMITATIONS. UNLIKE AN ACTUAL PERFORMANCE RECORD, SIMULATED RESULTS DO NOT REPRESENT ACTUAL TRADING. ALSO, SINCE THE TRADES HAVE NOT BEEN EXECUTED, THE RESULTS MAY HAVE UNDER-OR-OVER COMPENSATED FOR THE IMPACT, IF ANY, OF CERTAIN MARKET FACTORS, SUCH AS LACK OF LIQUIDITY. SIMULATED TRADING PROGRAMS IN GENERAL ARE ALSO SUBJECT TO THE FACT THAT THEY ARE DESIGNED WITH THE BENEFIT OF HINDSIGHT. NO REPRESENTATION IS BEING MADE THAT ANY ACCOUNT WILL OR IS LIKELY TO ACHIEVE PROFIT OR LOSSES SIMILAR TO THOSE SHOWN.
