# mObridge A2B Custom Firmware

Unofficial firmware for the **DA-G2.Pro A2B Ford, product ID `0x202c`**. Do not use it on any other product.

- **Stable** (2.11.x): bug fixes. Recommended for everyone.
- **Beta** (2.12.x): new features, still being tested.

[All releases](https://github.com/leland331/mobridge-a2b-custom-firmware/releases)

| Channel | Release | Notes |
|---|---|---|
| Stable | LB-06 / 2.11.14 | [release notes](release-notes/LB-06.md) |
| Beta | LB-RC1 / 2.12.0 | [release notes](release-notes/LB-RC1.md) |

> **Use at your own risk.** This is an unofficial project, unaffiliated with mObridge. An update can leave
> the device unusable. No license is granted here for the manufacturer's firmware.

## Before updating

- Save your settings as a `.rax` backup with the official mObridge app.
- Keep a copy of a firmware you know works (stock or a previous release).
- Use stable power. Check the file against the SHA-256 in the release notes.

## Install

Load the `.fif` with the official mObridge app's firmware update. Don't disconnect power during the update.

## Roll back

1. Flash a different firmware over it (a previous release or stock) with the official app. Answer **Yes** if it
   asks about an older or equal version. Restore your `.rax` if needed.
2. If the unit no longer starts normally, its bootloader takes over on its own (the bootloader is never
   changed by these releases). Connect the official app and use **Firmware Recovery** to flash a known-good `.fif`.

## Planned

- Centre and surround upmixing (frequency- and time-based, similar to Logic 7 / Pro Logic II).
- Speed-dependent EQ and volume.
