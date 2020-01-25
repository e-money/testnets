# e-Money Test Networks

We are launching a series of testnets to conduct testing before mainnet launch. We invite everybody to join!

Help and assistance is available in our [validator hangout group](https://t.me/joinchat/HBB5elfpWv8rADBFhhjbtg).

## Latest Test Network

Chain ID: lilmermaid-5  
Genesis:  https://raw.githubusercontent.com/e-money/testnets/master/lilmermaid-5/genesis.json  
Software: [v0.5.8](https://github.com/e-money/em-ledger/releases/tag/v0.5.8)  
Explorer: https://e-money.network *  

\* The block explorer does not accurately display multiple denominations yet.

## Seed Nodes

```
6ffb1e450a9efed17aead62a4dd9e453e2ee5c4d@3.123.252.230:26656  
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
emcli tx send faucet <your-validator> "500000000000ungm,500000000000eeur,500000000000echf,500000000000eusd,5000000000000ejpy" --gas-prices "0.8ungm"
```

## Rewards
*NOTICE: The reward program has ended as of 24/01/2020 12:00 UTC as a strong validator set has formed. Rewards will only be paid out to validators who joined a testnet before the deadline.*

Validators who participated in the testnets will be rewarded for their support as follows:

2000 NGM* for each testnet they participated in (lilmermaid-3 and later)  
5000 NGM* bonus for joining mainnet within 24 hours  

As the mainnet launch will be centralized, rewards can be paid out to validators on request and rewards can used to self-bond. 

\* Please note the NGM token is currently not tradeable, but will be sold during the [token presale](https://e-money.com/presale.html) for EUR 0.50. 

The following participants are eligible for rewards:

| Validator  | lilmermaid-1 | lilmermaid-2 | lilmermaid-3 | lilmermaid-4 | lilmermaid-5 |
|------------|---------------|--------------|--------------|--------------|--------------|
| 01node | - | - | + | + | + H |
| alexandruast | - | - | - | - | + H |
| ATEAM | - | - | + | + | + H |
| B-Harvest | - | - | + | - |  |
| BasBlock | - | - | - | - | + H |
| Bit Cat | - | - | + | + | + H |
| blockscape | - | - | - | - | + H |
| ChainLayer | - | - | + | + | + H |
| Cryptium Labs | - | - | - | + | + |
| Cosmostation | - | - | + | - |  |
| DCC Capital | - | - | - | + | + |
| DokiaCapital | - | - | - | + | + H |
| Easy2Stake | - | - | + | + | + H |
| Figment Networks | - | - | + | - | + |
| Forbole | - | - | + | + | + H |
| InchainWorks | - | - | - | - | + H |
| Inotel | - | - | - | + | + H |
| IRISnet-Bianjie | - | - | - | + | + |
| IW | - | - | - | - | + H |
| kytzu | - | - | - | + | + H |
| melea | - | - | - | + | + H |
| mintonium | - | - | - | + | + H |
| marssuper | - | - | - | + | + |
| Nodeasy.com | - | - | - | + | + |
| Northern Stake | - | - | - | + | + |
| Mr. K | - | - | - | + | + |
| novy | - | - | + | + | + |
| POS Bakerz | - | - | - | + |  |
| retz80 | - | - | - | + | + |
| Simply VC | - | - | + | + | + H |
| stake.zone | - | - | - | + | + |
| Stake5 Labs | - | - | - | + | + |
| stakewolf | - | - | - | + | + H |
| syncnode | - | - | - | + | + H |
| UbikCapital | - | - | + | + | + H |
| validator.network | + | + | + | + | + H |
| witval | - | - | - | + | + H |
| WeStaking | - | - | - | + | + H |
| xt | - | - | - | - | + |
