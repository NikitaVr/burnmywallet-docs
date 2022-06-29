---
sidebar_position: 1
---

# Intro

[View it on Github](https://github.com/NikitaVr/burnmywallet/blob/main/smart-contracts/contracts/BurnMyWallet.sol)

The BURN contract works by minting a soulbound token into your wallet.

This token is non transferable, once it is in your wallet it cannot be removed.

The BURN token can also only be minted into the signer's wallet, a wallet cannot burn another wallet.

## Gas Fees and Metatransactions

Currently you do need some funds in your wallet to cover gas fees.

We are working on solving this so you can sign the transaction from the hacked wallet, but pay the gas fees from a second safe wallet, this will make sure you can still burn your wallet even when all funds have been drained.

This will be implemented using Metatransactions and the [Gas Station Network (OpenGSN)](https://opengsn.org/)
