# e-Money Test Networks

We are running testnets in preparation for mainnet upgrades and to provide a safe environment for testing. We invite everybody to join!

Help and assistance is available in our [validator hangout group](https://t.me/joinchat/HBB5elfpWv8rADBFhhjbtg).

## Latest Test Network

Chain ID: lilmermaid-7  
Genesis:  https://raw.githubusercontent.com/e-money/testnets/master/lilmermaid-7/genesis.json  
Software: [v0.8.0](https://github.com/e-money/em-ledger/releases/tag/v0.8.0)  
Token API: https://beta-api.e-money.com/v1/tokens.json  
Explorer: https://beta.e-money.network  

## Seed Nodes

```
e2bef7a7adc5f0a2a471120a5fa92e94ef3fd62c@52.59.214.14:26656  
```

## Faucet

There is a faucet account available that is entirely self-service, with a few conditions:

1) Only take what you need
2) Return what you don't need
3) We'll top up as needed

Use `emcli keys add --recover faucet` to add the faucet account using the below mnemonic:
```
Mnemonic: satisfy select word swamp solar silver flavor sting screen novel deny win tape cement hole embark pact purpose goat latin gesture orange swift maple
Address:  emoney1j7sq6dadld46vruk92r0se0tv0f3uc4pvl4ntd
```

We suggest using the following command to transfer from the faucet:
```
emcli tx send faucet <your-validator> "500000000ungm" --gas-prices "1.0ungm"
```
