# Kelvin Console for ABCMint

This project provides a wallet desktop application for ABCMint.


## Download

Go to the [Releases](https://github.com/KelvinWallet/abcmint-console/releases)
page to download the latest version for Windows 10 and macOS.


## What is it

This is a wallet implementation for ABCMint, the post-quantum fork of Bitcoin
that uses Rainbow signature scheme.

This wallet implementation derives your Rainbow private keys from a BIP-39
mnemonic sentence (24 English words) using a deterministic algorithm.  Thus you
only need to backup one secret mnemonic sentence just like how you would do for
Bitcoin.


## Hot Wallet and Cold Walelt Mode

This app has two types of wallets.  The "Hot Wallet" mode means storing the
mnemonic and managing private keys all on your desktop in encrypted format.
The "Cold Wallet" mode means storing the mnemonic on a secure hardware device
"KelvinWallet".


## Existing Accounts?

If you have existing accounts created using [official abcmint
client](https://github.com/abcmint/abcmint), you won't be able to import its
private key file into Kelvin Console directly.  You must create a new account
in Kelvin Console, and transfer your funds into the new account.


## Report Issues

If you find any issues, feel free to open issue tickets using GitHub.
