# Panacea Testnet Networks
![banner](./banner.png)

This repo collects the genesis and configuration files for the various Panacea testnets. 


## General Testnet

- Version: [v1.3.3](https://github.com/medibloc/panacea-core/releases/tag/v1.3.3)
- Chain ID: `hygieia-3`
- Genesis file: https://github.com/medibloc/panacea-networks/raw/master/hygieia-3/genesis.json

### Persistent Peers

Open `$HOME/.panacead/config/config.toml` and edit a line starting with `persistent_peers` as below.
```
persistent_peers = "22ef7df8f45ae6c31cfd65aade415549a3d96f98@52.78.196.16:26656"
```
