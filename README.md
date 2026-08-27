# Panacea Testnet

The Panacea Testnet is a playground to test transactions and queries.

This repo contains genesis files of all historical chains of the Panacea Testnet.

## Intro

- Version: Panacea Core [v2.3.1](https://github.com/medibloc/panacea-core/releases/tag/v2.3.1)
- Chain ID: `hygieia-1`
- Genesis file: https://github.com/medibloc/panacea-testnet/raw/master/hygieia-1/genesis.json


## Persistent Peers

The public node below is operated by MediBloc with [PEX](https://docs.cosmos.network/cometbft/latest/spec/p2p/legacy-docs/P2P-Config) enabled.

You can add it to the `persistent_peers` in your `config.toml`. For more details, please see the [CometBFT documentation](https://docs.cosmos.network/cometbft/latest/docs/core/Using-CometBFT).

```
2fa36b0c6aabac0cd0dfb1634e95c66ff831edb6@54.180.204.250:26656
```


## Public Endpoints

Several public endpoints are provided by MediBloc.
**But, we highly recommend to run your own full node for high availability and reliability.**

- Cosmos REST: https://testnet-api.gopanacea.org
- Cosmos gRPC: https://testnet-grpc.gopanacea.org
- CometBFT RPC: https://testnet-rpc.gopanacea.org


## Faucet

You can send credit requests to the faucet by the following HTTP POST. Then, 10 MED will be transferred to your address. The faucet can handle only 5 requests per second.
```
curl --header "Content-Type: application/json" \
  --request POST \
  --data '{"denom":"umed","address":"<your_address>"}' \
  https://testnet-faucet.gopanacea.org/credit
```
