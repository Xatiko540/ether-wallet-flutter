## Ethereum wallet using an [ERC-20](https://en.wikipedia.org/wiki/ERC-20) smart contract.

A digital wallet app developed in dart and flutter. The idea is to help developers to understand how to build dApps using blockchain and associated technologies. This app can transfer tokens from one wallet to another through an [ERC-20](https://en.wikipedia.org/wiki/ERC-20) Ethereum contract.

### What's being used

- Built in [Flutter](https://flutter.dev/docs/get-started/install) framework
- [QR code scanner](https://github.com/juliuscanute/qr_code_scanner) to scan addresses
- [Web3Dart](https://github.com/simolus3/web3dart) to interact with Ethereum blockchain
- [Flutter hooks](https://github.com/rrousselGit/flutter_hooks) to manage widget life-cycle.
- [Solidity](https://github.com/allanclempe/ether-wallet-contract) smart contract

|                               Wallet                               |                              Change network                              |                               Transfer tokens                               |
| :----------------------------------------------------------------: | :----------------------------------------------------------------------: | :-------------------------------------------------------------------------: |
| ![Your wallet](https://faucet.clempe.dev/images/your-wallet-3.png) | ![Change network](https://faucet.clempe.dev/images/change-network-3.png) | ![Transfer tokens](https://faucet.clempe.dev/images/transfer-address-3.png) |

### Getting started

How to watch/build autogenerated files

```bash
$ flutter packages pub run build_runner build   # to build
$ flutter packages pub run build_runner watch   # to watch
```

How to run the app

```bash
$ flutter pub get packages
$ flutter packages pub run build_runner build
$ flutter run
```

running on the browser

```bash
$ flutter run -d web-server
```

How to run tests

```bash
$ flutter test
```

### Wallet balance

For those who don't want to play with smart contracts yet, you can claim some test tokens by following links below, or [check this repo](https://github.com/Xatiko540/ether-wallet-contract) to understand how to deploy your own contract.

**_Transfer test TOKENS to your wallet:_**

After setting up your wallet, you will need some tokens to play with. Use the link below to transfer some tokens to your wallet.

[https://faucet.clempe.dev](https://faucet.clempe.dev)

**_Transfer test Ether to your wallet_**

To process transactions on the network, you will also need coins to pay the transaction fees (gas). Use one of the following links to claim some coins depending on the network you are working on:

- Goerli: [https://goerlifaucet.com/](https://goerlifaucet.com/)
- Polygon (old MATIC): [https://faucet.polygon.technology/](https://faucet.polygon.technology/)
- BSC: [https://testnet.binance.org/faucet-smart](https://testnet.binance.org/faucet-smart)

### The smart contract

Link for the smart contract used for this project [https://github.com/Xatiko540/ether-wallet-contract](https://github.com/allanclempe/ether-wallet-contract)



