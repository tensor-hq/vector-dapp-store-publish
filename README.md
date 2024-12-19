# Vector Solana Dapp Store Publishing

## Prereqs

- Copy Google-signed APK to files/vector.apk

## Build

Signing pubkey: `3A9HveuPTaj2EUHLhukfJME49FbEEWCyNAUTdQwy1vRm`

```sh
pnpm i
npx dapp-store --help

export RPC="<RPC URL>"

# First time
just create_publisher
just create_app

# New release
just create_app_release

# First Submit
just publish_app_release
```
