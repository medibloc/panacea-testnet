# Panacea Testnet

The Panacea Testnet is a playground to test transactions and queries.

This repo contains genesis files of all historical chains of the Panacea Testnet.

## Intro

- Version: Panacea Core [v2.0.6](https://github.com/medibloc/panacea-core/releases/tag/v2.0.6)
- Chain ID: `hygieia-9`
- Genesis file: https://github.com/medibloc/panacea-testnet/raw/master/hygieia-9/genesis.json


## Persistent Peers

These public nodes below are operated by MediBloc with [PEX](https://docs.tendermint.com/master/spec/p2p/messages/pex.html) enabled.

You can add them to the `persistent_peers` in your `config.toml`. For more details, please see the [Tendermint document](https://docs.tendermint.com/master/tendermint-core/using-tendermint.html#peers).

```
c3fd461b3e2b0d7ff75034e94d295440fc1faa2d@54.180.204.250:26656
3a0cf95d83e891163c181612dad0db259f310772@3.34.67.40:26656
```


## Node Operations Guide

See the [Join Testnet](https://docs.gopanacea.org/for-validators/3-join-mainnet-testnet) guide.


## Public Endpoints

Several public endpoints are provided by MediBloc.
**But, we highly recommend to run your own full node for high availability and reliability.**

- Cosmos REST: https://testnet-api.gopanacea.org
- Cosmos gRPC: https://testnet-grpc.gopanacea.org
- Tendermint RPC: https://testnet-rpc.gopanacea.org


## Explorer

You can use an [explorer](https://testnet-explorer.gopanacea.org/) based on Big-Dipper.


## Faucet

You can send credit requests to the faucet by the following HTTP POST. Then, 10 MED will be transferred to your address. The faucet can handle only 5 requests per second.
```
curl --header "Content-Type: application/json" \
  --request POST \
  --data '{"denom":"umed","address":"<your_address>"}' \
  https://testnet-faucet.gopanacea.org/credit
```
