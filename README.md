# *Dotabata*TV
![](https://github.com/MineEric64/DotabataTV/blob/main/docs.jpg?raw=true)

 > [!NOTE]
 > MACD + Stochastic + Heikin Ashi + Quad EMA
>
Made for TradingView **Free users**

## Overview
Are you tired because of reached 2 maximum indicators? These two indicators include four core indicators frequently used. (Four-in-Two)

These two indicators consist of:
- **Vol. 1**: MACD + Stochastic
- **Vol. 2**: Heikin Ashi + Quad EMA

## How to apply
0. Before you should check that you created TradingView account and selected the symbol you want
1. Click 'Indicators' > 'My scripts'
2. Click the button 'Create script'
3. Copy the content of script file you want apply ([Vol. 1](https://github.com/MineEric64/DotabataTV/blob/main/vol1.pine), [Vol. 2](https://github.com/MineEric64/DotabataTV/blob/main/vol2.pine))
4. Paste it to Pine Editor in TradingView
5. Click the button 'Add to chart'
6. Enjoy!

Also, There's a tutorial video about inserting script: https://youtu.be/7gkoHKQPee8

## Note
MACD and Stochastic, Both of them are combined in one graph, so you might be confused how to read them.

MACD is normal, so you can read as usual.

But, Stochastic is a little bit different. The range is changed to:

- Original Range: 0 ~ 100
- Changed Range (in graph): Dynamic, MACD based

You can read it like:
- Upper Band (80%, Overbought): Above Gray Line
- Middle Band (50%): 0
- Lower Band (20%, Oversold): Below Gray Line

The red Line is Upper/Lower Bounds Line (Limit).

 > [!WARNING]
 > **Stochastic range can be changed dynamically!** If you don't want, Please disable 'Use Stochastic Fixed Range'.
>
When disabling, you need to change 'Stochastic Fixed Range Value' based on MACD indicator.
The default value is 1, which stochastic range is -1.0 ~ 1.0.

Also the color of 'Vol. 1' plots mean:
- Thick Magenta line: MACD (MACD)
- Thick Dark gray line: Signal (MACD)
- Blue line: %K (Stochastic)
- Orange line: %D (Stochastic)

You should keep in mind these!

## And...

Also, I personally recommend using [DIY Custom Strategy Builder](https://www.tradingview.com/v/Oun5v3Zq/) too. This is extremely powerful tool (All-in-One) and Dotabata was inspired by this.

Related tutorial videos:
- https://youtu.be/XV2GDNKnElI (Recommended, Simple)
- https://youtu.be/Vsg-PxVpMK8 (More details)

## Credits
- Moving Average Convergence Divergence by TradingView
- Stochastic by TradingView
- [Heikin Ashi](https://www.tradingview.com/v/NbYBiQdn/) by CaptainCoinFlip
- [Three Moving Averages](https://www.tradingview.com/v/reIK2us9/) by AdventTrading

A number of the embedded indicators within this tool are the creations of esteemed Pine Script developers from the TradingView community and others, thanks them a lot.
