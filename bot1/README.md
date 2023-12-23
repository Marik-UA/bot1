![](https://media.discordapp.net/attachments/876447732259225612/1166747031101001888/icon.png?ex=654b9cd9&is=653927d9&hm=35e99bcf07f2aaa8726daf14b3c16ecf3917894e8e292990c5b0d134d3927318&=&width=87&height=117)

# BARBOTINE ARBITRAGE

## __BEGINNER INSTRUCTIONS__

## How to add an exchange?

1. Go to the exchange\_config.py file with any text editor.
1. Locate the ‘ex’ variable ([screenshot](https://media.discordapp.net/attachments/876447732259225612/1163819298301673552/Capture_decran_2023-10-17_a_14.41.46.png?ex=6540f62f&is=652e812f&hm=cb5fbf0a2367f8e1a65a7f4093738af1153733a776933f6d82ee4552e7983f54&=&width=1620&height=764)).
1. Add the exchange you want among the [compatible exchanges](https://github.com/ccxt/ccxt).
1. Add you api keys if you want it to trade with your account ([screenshot](https://media.discordapp.net/attachments/876447732259225612/1163820636842508481/image.png?ex=6540f76e&is=652e826e&hm=80f84bebf2a0b9f29d8b8fcd8b4d2e6415486af224a627cb3ea95273d56b596b&=&width=2106&height=1170))

## Can I run the bot with multiple assets?

No, you can’t. As Barbotine Arbitrage is working with instantaneous transfers ([read this](https://medium.com/@barbotine-arbitrage/how-to-exploit-arbitrage-opportunities-using-python-in-centralized-exchanges-like-binance-or-kucoin-805b5bf7b2f2)), the bot has to buy the assets before, to have half USDT / half crypto. So you can run multiples instances of Barbotine Arbitrage with a part of your portfolio to run with multiple assets, but the profits will be proportionally smaller, it will end up being probably the same, maybe you’ll lose with the trading fees.

## Can we predict an asset with which I will have profits ?

Yes it might be possible, but currently, the arbitrage bot only operates with a manual symbol selection.
