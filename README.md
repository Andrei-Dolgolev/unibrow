# unibrow

Uniswap development and testing environment.

## Setting up a test network

Test network requires at least 2 mining nodes, else chain data may not be persisted to disk between
runs.

To bring up a test network, run the [`testnet.bash`](./testnet.bash) script from the root of this
repository as follows:
```bash
mkdir -p testnet
TESTNET_BASE_DIR=testnet/ ./testnet.bash refresh
```

You can run the same command to restart the testnet after shutting it down using `CTRL+C`.

All the account passwords (by default) are `peppercat`.

## Deploying the Uniswap v3 Factory contract

