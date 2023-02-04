Estimate gas cost in USD

To get a USD estimation of gas cost, you'll need a COINMARKETCAP_API_KEY environment variable. You can get one for free from CoinMarketCap.

Then, uncomment the line coinmarketcap: COINMARKETCAP_API_KEY, in hardhat.config.js to get the USD estimation. Just note, everytime you run your tests it will use an API call, so it might make sense to have using coinmarketcap disabled until you need it. You can disable it by just commenting the line back out.