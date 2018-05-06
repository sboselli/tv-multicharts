# TradingView Multicharts

A set of static html files featuring various combinations of markets, using TradingView widgets.

See below for the full list of layouts.

Example screenshot: Bitfinex Longs & Shorts
![Bitfinex Longs & Shorts](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/example.png)

## Current layouts

* exchanges-btc (3x3) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/exchanges-btc.png))
  * BITFINEX:BTCUSD 1M | COINBASE:BTCUSD 1M | BITSTAMP:BTCUSD 1M
  * BITFLYER:Bitcoin/Yen 1M | BINANCE:Bitcoin/Tether 1M | BITTREX:Bitcoin/Tether 1M
  * BITHUMB:Bitcoin/Won 1M | XCOIN:Bitcoin/Won 1M | KORBIT:Bitcoin/Won 1M
* bitfinex-longs-shorts-btc (2x3) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/bitfinex-longs-shorts-btc.png))
  * BITFINEX:BTCUSD 1M | BITFINEX:BTCUSD 15M
  * BITFINEX:BTCUSDLONGS 1M | BITFINEX:BTCUSDLONGS 15M
  * BITFINEX:BTCUSDSHORTS 1M | BITFINEX:BTCUSDSHORTS 15M
* bitfinex-timeframes-btc (3x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/bitfinex-timeframes-btc.png))
  * BITFINEX:BTCUSD 1M | BITFINEX:BTCUSD 5M | BITFINEX:BTCUSD 15M
  * BITFINEX:BTCUSD 1H | BITFINEX:BTCUSD 4H | BITFINEX:BTCUSD 1D
* bitfinex-timeframes-eth (3x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/bitfinex-timeframes-eth.png))
  * BITFINEX:ETHUSD 1M | BITFINEX:ETHUSD 5M | BITFINEX:ETHUSD 15M
  * BITFINEX:ETHUSD 1H | BITFINEX:ETHUSD 4H | BITFINEX:ETHUSD 1D
* bitfinex-timeframes-ltc (3x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/bitfinex-timeframes-ltc.png))
  * BITFINEX:LTCUSD 1M | BITFINEX:LTCUSD 5M | BITFINEX:LTCUSD 15M
  * BITFINEX:LTCUSD 1H | BITFINEX:LTCUSD 4H | BITFINEX:LTCUSD 1D
* coinbase-timeframes-btc.html (3x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/coinbase-timeframes-btc.png))
  * COINBASE:BTCUSD 1M | COINBASE:BTCUSD 5M | COINBASE:BTCUSD 15M
  * COINBASE:BTCUSD 1H | COINBASE:BTCUSD 4H | COINBASE:BTCUSD 1D
* coinbase-timeframes-eth.html (3x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/coinbase-timeframes-eth.png))
  * COINBASE:ETHUSD 1M | COINBASE:ETHUSD 5M | COINBASE:ETHUSD 15M
  * COINBASE:ETHUSD 1H | COINBASE:ETHUSD 4H | COINBASE:ETHUSD 1D
* coinbase-timeframes-ltc.html (3x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/coinbase-timeframes-ltc.png))
  * COINBASE:LTCUSD 1M | COINBASE:LTCUSD 5M | COINBASE:LTCUSD 15M
  * COINBASE:LTCUSD 1H | COINBASE:LTCUSD 4H | COINBASE:LTCUSD 1D
* bitmex-contracts-btc (2x2) ([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/bitmex-contracts-btc.png))
  * BITMEX:XBT 1M | BITMEX:XBTUSD 1M
  * BITMEX:XBTH18 1M | BITMEX:XBTM18 1M
  * bitmex-contracts-btc (2x2)

* international-exchanges-btc-ltc-eth-bch-longs-shorts 3x3
([screenshot](https://raw.githubusercontent.com/sboselli/tv-multicharts/master/screenshots/international-exchanges-btc-ltc-eth-bch-longs-shorts.png))
  * BITFINEX:BTCUSD 1M | BITFINEX:USD PERPETUAL INVERSE 1M | BITFLYER:BTCYEN 1M
  * BINANCE:BTCTETHER 1M | COINBASE:BTCUSD 1M | BITSTAMP:BTCUSD 1M
  * BITFINEX:BTCUSD LONGS 1M | BITFINEX:BTCUSD SHORTS 1M | BITHUMB:BTC-SOUTH-KOREA-WON

## Grid

There's a simple grid setup that allows you to do 1x1 up to 5x5 layouts.

Beware, 4/5 columns/rows will only look good on larger resolutions.

## Contributing

Contributions are welcome! Submit a PR with your custom layouts.

You can target specific markets or exchanges, but please try to have a degree of unity and order in the layout as a whole. (and also please include it in this README).

## Support

If you find this useful consider subscribing to TradingView, it's a great tool.
