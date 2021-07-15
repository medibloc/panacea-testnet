# Panacea Testnet Networks

This repo collects the genesis and configuration files for the various Panacea testnets. 


## General Testnet

- Version: [v2.0.0](https://github.com/medibloc/panacea-core/releases/tag/v2.0.0)
- Chain ID: `hygieia-5`
- Genesis file: https://github.com/medibloc/panacea-networks/raw/master/hygieia-5/genesis.json

### Persistent Peers

Open `$HOME/.panacead/config/config.toml` and edit a line starting with `persistent_peers` as below.
```
persistent_peers = "22ef7df8f45ae6c31cfd65aade415549a3d96f98@52.78.196.16:26656"
```
