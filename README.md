# mObridge Custom Firmware

Unofficial firmware for the **DA-G2.Pro A2B Ford, product ID `0x202c`**.

[Download the latest release](https://github.com/leland331/mobridge-custom-firmware/releases/latest)

## Current release

**LB-06 / 2.11.14**, based on stock firmware **2.11.8**. It includes fixes for amp wake failures and ignition-on and shutdown snaps. See the [release notes](release-notes/LB-06.md) for details and checksums.

Installed and tested by the maintainer on one setup. Other hardware and vehicle combinations have not been validated.

## Before updating

- Confirm your device is the DA-G2.Pro A2B Ford with product ID `0x202c`. Do not use this firmware on another product.
- Save your settings as a `.rax` backup using the official mObridge app.
- Keep a copy of the correct stock firmware for your device in case you need to roll back.
- Use stable power throughout the update. Check the downloaded file against the SHA-256 in the release notes.

## Install

Use the official mObridge app's firmware update process to load the release `.fif` file. Do not disconnect power during the update. Afterward, check the reported version and test normal audio, chimes, wake and shutdown behavior.

## Roll back

Use the official app to install your device's correct stock firmware. If prompted about an older or equal version, confirm the downgrade. Restore your `.rax` settings backup if needed.

Bootloader recovery mode has been examined but has not been hardware tested. Recovery from firmware that will not boot is not guaranteed.

## About

This repository contains public firmware releases and their documentation. Future releases and a custom app may be added here.

This is an unofficial project, unaffiliated with mObridge. Use at your own risk; an update can leave the device unusable. No license is granted here for the manufacturer's firmware.
