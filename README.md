# ventoyimg

[![Build img](https://github.com/catherinedoyel/ventoyimg/actions/workflows/blank.yml/badge.svg)](https://github.com/catherinedoyel/ventoyimg/actions/workflows/blank.yml)

[Ventoy GitHub](https://github.com/Ventoy/Ventoy)

Do not rely on these releases yet. Any files you download labeled as build are not widely tested.

Pre-built disk images with Ventoy and a custom EFI boot menu (GParted Live not included but supported, Ventoy installer, KeyTool). Built automatically from the latest upstream Ventoy release.

> **Note:** This project is mostly superseded by
> [bootable-wiki/bwbundle](https://github.com/bootable-wiki/bwbundle) which
> provides a more comprehensive solution. These raw Ventoy images may still be
> useful for specific use cases.

The `.img.zip` files contain a Ventoy formatted disk image with `ventoy.json` pre-applied — just flash with any imaging tool.

# Using images (preferred solution)
If you want to try the .img.zip files I would recommend using the following software.
- [balenaEtcher for Windows, Mac & Linux](https://etcher.balena.io/)
- [Chromebook Recovery Utility for Windows, Mac, Linux & **ChromeOS**](https://chrome.google.com/webstore/detail/chromebook-recovery-utili/pocpnlppkickgojjlmhdmidojbmbodfm),
- [EtchDroid for Android ](https://play.google.com/store/apps/details?id=eu.depau.etchdroid)

when using EtchDroid you will first need to unzip and get the img file out of the zip folder. You may run into similar issue on a Chromebook.
As a part of using the .img.zip files I would recommend the 256MB one first to ensure that the process works correctly. Then get a bigger size once you know it works.

# Using EFI folder
If you cannot run software like this on your devices do not lose hope. Anything that can copy files out of a zip folder and put it on a fat32 formatted usb stick can work with an exception. The resulting flash drive will only work on 64 bit UEFI computers such as laptops made after Windows 8 (2012). Perhaps you can use a kiosk style computer like in a library or computer lab, with permission of course.

# Example zip file installation.

https://github.com/catherinedoyel/ventoyimg/assets/65094027/bc02c5f9-a103-443f-94be-3ab46257c9fe
