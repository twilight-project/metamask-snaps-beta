# MetaMask Snaps Beta Fork

Welcome to the MetaMask Snaps Beta. This repository is a fork of the regular [MetaMask extension](https://github.com/MetaMask/metamask-extension/) (and then re: Fork of [MetaMask-snaps-beta](https://github.com/MetaMask/metamask-snaps-beta).

The reason for this fork is to add twilight.finance domain names into the domain white-list. This has been done just for the educational purposes.

## Compilation Instructions

To compile you would need to clone the repo and then do `gulp dist` this will take a bit of time, afterwards go to Chrome/Brave Extensions and add `Load Unpacked` extension by browsing to `dist/chrome` directory (do not load Brave extension, that doesn't work even in Brave, Chrome extension works in Brave though!)

## Caution
As this is experimental software, please create a new test wallet (mnemonic) after installing the extension (do not use your main mnemonic!)

## MetaMask Snaps Details

MetaMask Snaps is the name for our [plugin system](https://medium.com/metamask/introducing-the-next-evolution-of-the-web3-wallet-4abdf801a4ee). Everything you need to know can be found in [the MetaMask Snaps Wiki](https://github.com/MetaMask/metamask-snaps-beta/wiki).

![MetaMask Snaps Logo](https://miro.medium.com/max/1492/1*3rV0z0ufTqkGC4RJ3vXQwA.png)
