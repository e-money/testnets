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
| 01node | + | + | + | 6000 | emoney1s34xgst5slleg22ey8gwnfd4yf977xrs3h5qej | 
| alexandruast | - | - | + | 2000 | emoney1ualhu3fjgg77g485gmyswkq3w0dp7gysshv0cz |
| ATEAM | + | + | + | 6000 | emoney1edxhamqghv5naa6gjtar5jgxg6ly2rt4qfhf4x |
| B-Harvest | + | - | + | 4000 | emoney1zgv6tqess9q6y4cj28ldpjllrqlyzqqhq004k3 |
| BasBlock | - | - | + | 2000 | emoney17v5v5nwqs9677u92us0qdare549tj7gn7pv78d |
| Bit Cat | + | + | + | 6000 | emoney1qk3a2lpm5mskwnpsjm25qzs9urqhwclmuqkejs |
| blockscape | - | - | + | 2000 | emoney1lyy7q6lt5gyt43sxms4tt9smcnrqy2j0nxt3wf |
| ChainLayer | + | + | + | 6000 | emoney1kgddca7qj96z0qcxr2c45z73cfl0c75p57l33h |
| Cryptium Labs | - | + | + | 4000 | |
| Cosmostation | + | - |  | 2000 | |
| DCC Capital | - | + | + | 4000 | emoney1q4k07zr7504f2tcdfpl4xmawlgq6yz4mzwhq7v |
| DokiaCapital | - | + | + | 4000 | emoney1z89utvygweg5l56fsk8ak7t6hh88fd0amftwj4 |
| Easy2Stake | + | + | + | 6000 | emoney1qjy6hpc65mp6yc7hf234y3sf0rtmumnt3dx44p | 
| Figment Networks | + | - | + | 4000 | |
| Forbole | + | + | + | 6000 | emoney1293pqwtzu67zp8txuya4yts03ccw5kgfz83kmf |
| InchainWorks | - | - | + | 2000 | |
| Inotel | - | + | + | 4000 | emoney17wcggpjx007uc09s8y4hwrj8f228mlweu9p4qf |
| IRISnet-Bianjie | - | + | + | 4000 | |
| IW | - | - | + | 2000 | |
| kytzu | - | + | + | 4000 | emoney1wtv0kp6ydt03edd8kyr5arr4f3yc52vpmty82j |
| melea | - | + | + | 4000 | emoney1cu84axdsggf2w3s4pgfg406p0ex9hp682gehrz |
| mintonium | - | + | + | 4000 |emoney1eq55wawvpv044z68tm456mdh8jgvlt32kftlzc |
| marssuper | - | + | + | 4000 | emoney1j40h49qch2kcx28pc892hmyl930skzzxlw75ax |
| Nodeasy.com | - | + | + | 4000 | emoney159uhuzucvmtftdappd4smuks4v7s0dpmcednm2 |
| Northern Stake | - | + | + | 4000 | emoney1hwvlth79tkzsk2vqnt7vkcncajtgzhm3wex6e3 |
| Mr. K | - | + | + | 4000 | emoney1cv4leeaavx5lu5n7jgrdklt76rgx2xtdw5df95 |
| novy | + | + | + | 6000 | emoney1q2kc675fw536jq74f6ekwae2pr5pksue22sn3a |
| POS Bakerz | - | + | + | 4000 | emoney1tw0qj9nuqx8nhn9d0zup64navtc0c4hdh9kxst |
| retz80 | - | + | + | 4000 | emoney1ygm45zwa7y6smay587rws60wptuauycmc0gf8r |
| Simply VC | + | + | + | 6000 | emoney1sz7rp920hgupfl0p6c7kwkaes8q8tx3luz3va4 |
| stake.zone | - | + | + | 4000 | emoney1tmu0fayvksthpt4qety8dn55lc8pg4sphyapz5 |
| Stake5 Labs | - | + | + | 4000 |emoney1d6q0xxdugldf85xhkjtw4q7tc5v46ff3ytezyu |
| stakewolf | - | + | + | 4000 |emoney1waqn2psrhs4vz5gz9p77hv9cxw3xcccffyph02 |
| syncnode | - | + | + | 4000 | emoney1s3x3wy58ssrjf7097406alryeejfamhrtgd0q5 |
| UbikCapital | + | + | + | 6000 | |
| validator.network | + | + | + | 6000 | emoney1sxx9mszve0gaedz5ld7qdkjkfv8z992avdth5f |
| witval | - | + | + | 4000 | emoney10nc3y5xp93txarcxcqdrsvh9ta297v7xkzs4yy |
| WeStaking | - | + | + | 4000 | emoney1ptyzewnns2kn37ewtmv6ppsvhdnmeapvp7kyl6 |
| xt | - | - | + | 2000 | |
