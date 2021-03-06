# Monero Monitor Extension

Copyright (c) 2015-2017 The Monero Monitor developers.


## License

This software is released under the terms of the MIT license. See `LICENSE` for
more information or see http://opensource.org/licenses/MIT.


## About

[![Available in the Chrome Store](extras/ChromeWebStore_BadgeWBorder_v2_206x58.png)](https://chrome.google.com/webstore/detail/monero-monitor/ojekadcfnkkihlleaafggfgbggdckpgo)

This Chrome extension allows the user to easily monitor basic Monero network
statistics, including network hashrate; the most recent block, time, and reward;
network difficulty; and total coin supply.  This extension also provides easy access
to the current XMR exchange rates on the Poloniex exchange. Also, the extension
provides easy access to the current top posts on the /r/monero subreddit. Users can
enable an additional tab to monitor mining status on a number of XMR mining pools.


## Installation
To build this extension from source,

    git clone https://github.com/monero-monitor/monero-monitor

    cd monero-monitor

    ./build-chrome.sh

Install in Chrome:

1) Navigate to chrome://extensions

2) Enable Developer Mode

3) Load Unpacked Extension located at:

    /path/to/monero-monitor/build/chrome


## External Public APIs Used

* Powered by [CoinDesk](http://www.coindesk.com/price/)
* Monero network info from [MoneroBlocks API](http://moneroblocks.info/api)
* Market information from [Poloniex API](https://poloniex.com/support/api)
* Various mining pools using the [node-cryptonote-pool](https://github.com/zone117x/node-cryptonote-pool) source.


## Contributing

Please feel free to fork, submit pull requests or issues, or otherwise contribute
in making this extension as useful as possible.


If you find this extension useful, please consider donating to the developer:

`49VtwYXDbbh7hq57wwkLH36x4D6XV6Tr2P93ANnBi9qFGyYZbx8SXWPUHC9V1o7N41b4c3WJ1kubkffRfPTPfMuB8QUqFD5`

## Screenshots

![Overview](extras/screenshots/01-network.png)

![Markets](extras/screenshots/02-markets.png)

![Mining](extras/screenshots/03-mining.png)

![reddit](extras/screenshots/04-reddit.png)

![Options](extras/screenshots/05-options.png)
