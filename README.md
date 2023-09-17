# Foundry DEFI Stablecoin

1. Relative Stability: Anchored or Pegged -> $1.00
    1. Chainlink price feed
    2. Set a function to exchange ETH & BTC -> $$$
2. Stability Mechanism (Minting): Algorithmic (Decentralized)
    1. People can only mint the stablecoin iwth enough collateral (coded)
3. Collateral Type: Exogenous (Crypto)
    1. wETH
    2. wBTC

- calculate health factor function
- set health factor if debt is 0
- Added a bunch of view functions

1. What are our invariants/properties?

## Usage

### Build

```shell
forge build
```

### Test

```shell
forge test
```

### Format

```shell
forge fmt
```

### Gas Snapshots

```shell
forge snapshot
```

### Anvil

```shell
anvil
```

### Deploy

```shell
forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
cast <subcommand>
```

### Help

```shell
forge --help
anvil --help
cast --help
```
