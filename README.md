# e-Money Test Networks

We are launching a series of testnets to conduct testing before mainnet launch. We invite everybody to join!

Help and assistance is available in our [validator hangout group](https://t.me/joinchat/HBB5elfpWv8rADBFhhjbtg).

## Latest Test Network

Chain ID: lilmermaid-5  
Genesis:  https://raw.githubusercontent.com/e-money/testnets/master/lilmermaid-5/genesis.json  
Software: [v0.5.12](https://github.com/e-money/em-ledger/releases/tag/v0.5.12)  
Explorer: https://e-money.network  

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

Participation rewards will be paid out to validators in the genesis block. The bonus will be paid out to the same address upon joining the mainnet within 24 hours.  

\* Please note the NGM token is currently not tradeable, but will be sold during the [token presale](https://e-money.com/presale.html) for EUR 0.50. 

**Please create a pull request to add your address below.** The below participants are eligible for rewards:

| Validator  | lilmermaid-3 | lilmermaid-4 | lilmermaid-5 | Rewards (NGM) | Address |
|------------|---------------|--------------|--------------|---------------|---------|
| 01node | + | + | + | 6000 | |
| alexandruast | - | - | + | 2000 | |
| ATEAM | + | + | + | 6000 | |
| B-Harvest | + | - | + | 4000 | |
| BasBlock | - | - | + | 2000 | |
| Bit Cat | + | + | + | 6000 | |
| blockscape | - | - | + | 2000 | |
| ChainLayer | + | + | + | 6000 | |
| Cryptium Labs | - | + | + | 4000 | |
| Cosmostation | + | - |  | 2000 | |
| DCC Capital | - | + | + | 4000 | |
| DokiaCapital | - | + | + | 4000 | |
| Easy2Stake | + | + | + | 6000 | |
| Figment Networks | + | - | + | 4000 | |
| Forbole | + | + | + | 6000 | |
| InchainWorks | - | - | + | 2000 | |
| Inotel | - | + | + | 4000 | |
| IRISnet-Bianjie | - | + | + | 4000 | |
| IW | - | - | + | 2000 | |
| kytzu | - | + | + | 4000 | emoney1wtv0kp6ydt03edd8kyr5arr4f3yc52vpmty82j |
| melea | - | + | + | 4000 | |
| mintonium | - | + | + | 4000 | |
| marssuper | - | + | + | 4000 | |
| Nodeasy.com | - | + | + | 4000 | |
| Northern Stake | - | + | + | 4000 | |
| Mr. K | - | + | + | 4000 | |
| novy | + | + | + | 6000 | |
| POS Bakerz | - | + |  | 2000 | |
| retz80 | - | + | + | 4000 | |
| Simply VC | + | + | + | 6000 | |
| stake.zone | - | + | + | 4000 | |
| Stake5 Labs | - | + | + | 4000 | |
| stakewolf | - | + | + | 4000 | |
| syncnode | - | + | + | 4000 | |
| UbikCapital | + | + | + | 6000 | |
| validator.network | + | + | + | 6000 | emoney1sxx9mszve0gaedz5ld7qdkjkfv8z992avdth5f |
| witval | - | + | + | 4000 | |
| WeStaking | - | + | + | 4000 | |
| xt | - | - | + | 2000 | |
