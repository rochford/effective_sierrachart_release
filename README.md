# effective_sierrachart

##

Visit https://www.theaceofcharts.com/products/effective-sierrachart/

## Introduction

Release v4.0.1

This is developed for myself and might be useful for you. A study collection to allow better understanding of Value Areas, Gaps, absorption, exhaustion and momentum.

Here is a sample screenshot: ![SCREENSHOT](http://github.com/rochford/effective_sierrachart_release/blob/main/docs/effective_main.png)

## Cost

Can be used without charge or commitment for first month. After that it will cost 20 USD per month with payment made by Paypal using a link provided to you in email. I will request payment in email communication. 

## Installation and Configuration

The study will not load if your Sierra Chart username has not been authorized me. Email me (timothy.rochford@gmail.com) your Sierra Chart account name. 

Your Sierra Chart account name is listed here: https://www.sierrachart.com/UserControlPanel.php#AccountDetails

Download the Effective Studies file https://github.com/rochford/effective_sierrachart_release/releases/download/v4.0.1/effectiveStudies_64.dll on this website and follow these steps: https://www.sierrachart.com/index.php?page=doc/UsingAdvancedCustomStudies.php#ManuallyInstallingAdvancedCustomStudyRelatedFiles 
Common problems are described here: https://www.sierrachart.com/index.php?page=doc/UsingAdvancedCustomStudies.php

### Effective Main Study setup

IN5: Effective Main Study depends upon Numbers Bar Calculated Values. Supply the StudyID of it.  

### Effective Volume Imbalance Study setup

This study requires some setup. "Volume At Price Threshold Alert V2" study must be on the chart twice. One configuration needs to highlight Bid price level imbalances and another study configuration needs to highlight Ask price level imbalances.
See https://www.sierrachart.com/index.php?page=doc/StudiesReference.php&ID=386 . Once these 2 studies are on the chart, the Effective Volume Imbalance Study Input IN5 and IN6 need to have the study ID's set. 

## Inputs

## Subgraphs

Exhaustion (Exhausted Sellers and Buyers),
BarBidAskImbalance (Bullish and Bearish),
PriceLevelBidAskImbalanceUp,
PriceLevelBidAskImbalanceDown,
SlingShotPoc (Bullish and Bearish),
PairedPoc,
PocWave (Bullish and Bearish),
ZeroPrint (Bullish and Bearish),
UntestedValueAreaProminentPoc (Bullish and Bearish),
EngulfingValueArea (Bullish and Bearish),
Ratio (Bullish and Bearish),
Gap between value areas,
VolumeDecline  (Bullish and Bearish),
RetailSuck (Bullish and Bearish),
DeltaTail  (Bullish and Bearish),
OpenPoc (Bullish and Bearish),
AboveAbove (Bullish),
BelowBelow (Bearish),
ValueAreaIsland (Bullish and Bearish)

In addition to subgraphs, extension lines for Untested Value Areas, gaps between value areas, thin prints, Prominent Point Of Controls and Open Point of Control lookback bars can be configured to be drawn.

### VolumeImbalance

Example: ![SCREENSHOT](http://github.com/rochford/effective_sierrachart_release/blob/main/docs/volumeImbalance.png)
The imbalances do not need to be adjacent (stacked) and can be anywhere in the bar. 
A sustained imblanance in a bar is where there was a same imbalance in the previous bar. Usually a sign of sustained trading at a level.

## Notes

Tested with 1 minute and 8 range 6E EuroCurrency charts. Other symbols and chart types are untested but should work. 

## Disclaimer

This tool and material is for educational and informational purposes only and should not be considered a
solicitation to buy or sell a futures contract or make any other type of investment decision. Futures
trading contains substantial risk and is not for every investor. An investor could potentially lose all or
more than the initial investment. Risk capital is money that can be lost without jeopardizing ones
financial security or life style. Only risk capital should be used for trading and only those with sufficient
risk capital should consider trading. Past performance is not necessarily indicative of future results.

CFTC Rules 4.41 - Hypothetical or Simulated performance results have certain limitations, unlike an
actual performance record, simulated results do not represent actual trading. Also, since the trades have
not been executed, the results may have under-or-over compensated for the impact, if any, of certain
market factors, such as lack of liquidity. Simulated trading programs in general are also subject to the
fact that they are designed with the benefit of hindsight. No representation is being made that any
account will or is likely to achieve profit or losses similar to those shown
