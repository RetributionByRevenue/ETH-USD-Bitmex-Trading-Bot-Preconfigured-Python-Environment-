# ETH-USD-Bitmex-Trading-Bot

The purpose of this github is to provide a preconfigured trading ready python environment to all of those whom wish to explore and learn the exciting domains of cryptocurrency and quantitative finance.  This very simple trading bot places long and short orders on eth/usd. 

![Output Result](https://github.com/RetributionByRevenue/ETH-USD-Bitmex-Trading-Bot/blob/master/demonstration.gif?raw=true?)

What is this?
I anticipate many viewers of this page to be complete scrubs and incompetent algo traders, so i took the liberty to configure a portable and containerized python environment making it so new people can instantly compile and execute my included programs without issues. Technically speaking, it would be too difficult for python beginners to install such things as TA-LIB and Pandas Data-frame, so this should be all new python users definitive python environment otherwise. 

How does it work?
Just open spyder.exe and load bitmex_tradingbot.py. (Yes that's all you need to do.)  Due to the nature of Winpython being portable and containerized (easy for me to share), there is no need to install anything.  All you need to do is download and extract the python trading environment from the download link provided. 

What does the trading bot do?
Demonstrates how to connect to the bitmex api, supports leverage, usage of trading technical indicators, web scraping, very smart logic regarding algo and market state management(most import thing here), order take profits, and order stop losses.  Also included a Debug mode to force states and algorithm values (for testing purposes) to help orient the logic in specific ways in order to simulate potential real life trading conditions that could occur.  

What's the catch? 
This works on windows. If you are using Linux, then you are smart enough to compile the code. Rip Mac users(unless you are python girl :3 ).

Fundamentally speaking, this trading bot is a skeleton or a blank canvas. It is up to you to provide the skeleton with a smart brain among other things in order to take your algo trading to the next level. This trading bot here is only 300 lines of code, but the one i use in real life is 1700 lines of code so there is much to be added such as machine learning. 

Download Link: https://mega.nz/#!LxMTSC4S!x4pZDwHKAx8Y84qv26GEfqZ6RlgWMAtNHYMKwflkbLQ

Click image below to watch Youtube video tutorial:
[![Link to youtube video](https://github.com/RetributionByRevenue/ETH-USD-Bitmex-Trading-Bot-Preconfigured-Python-Environment-/blob/master/thumbnail.png?raw=true)](https://www.youtube.com/watch?v=cDTZwG3nqco&t=478s)

| Tech Stack Used   |      Description      |  Link |
|----------|:-------------:|------:|
| Mazmex7's Bitmex Wrapper |  Better than official Bitmex api | https://github.com/mazmex7/BitMEX-API-python |
| WinPython |   A powerful portable python environment with many useful tools preinstalled. | http://winpython.sourceforge.net/ |
| CCXT | Obtains Candlestick Data in a nice manner |   https://github.com/ccxt/ccxt  |

Don't need donation. Free and open source software, you are welcome to modify and share. 
