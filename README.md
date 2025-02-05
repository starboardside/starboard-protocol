# Starboard Side Finance
All hands to Starboard Side! ⛵

The Starboard Protocol is a governance aggregation protocol which boosts rewards for delegates and provides additional protections for related DAOs. Learn more: https://starboardside.finance/

This repo contains the code for smart contracts and the Starboard Protocol which operate the governance module for Starboard Side:
- Converts gauges into OZ Governor
- Provides additional protections for DAOs, for example enforcing that gauges can not be used for security council votes
- Connects to Enzyme Vaults for deposits

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
