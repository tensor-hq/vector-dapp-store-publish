# Vector Solana Dapp Store Publishing

Signing pubkey: `3A9HveuPTaj2EUHLhukfJME49FbEEWCyNAUTdQwy1vRm`

```sh
yarn
yarn dapp-store --help

# First time
yarn dapp-store create publisher -k ~/.config/solana/dapp_store.json -u https://api.mainnet-beta.solana.com
yarn dapp-store create app -k ~/.config/solana/dapp_store.json -u https://api.mainnet-beta.solana.com

# New release
yarn dapp-store create release -k ~/.config/solana/dapp_store.json -u https://api.mainnet-beta.solana.com

# Submit
yarn dapp-store publish submit -k ~/.config/solana/dapp_store.json -u https://api.mainnet-beta.solana.com
```
