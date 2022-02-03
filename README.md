# Coinex CLI

Command line interface written in Node.js to check cryptocurrency prices

Register and Get Your API key at https://nomics.com

## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
coinex -h

# Version
coinex -V

# API Key Commands
coinex key set
coinex key show
coinex key remove

# Crypto Check Commands
coinex check price

# Check Specific Coins (default: BTN,ETH,XRP)
coinex check --coin=BTC,ETH

# Choose Currency (Default: USD)
coinex check --cur=EUR
```

### Version

1.0.0

### License

MIT
