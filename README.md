<h1 align="center"> Dell Inspiron G7 7588 Hackintosh </h1>

## Announcement: Because the EFI is very stable until now and also I've just sold my G7 and bought a Macbook Pro M1. So start from this month, Nov 2022, I will no longer update my EFI and leave the GitHub repo as is.

<p align="center">
  <img src="./asset/g7.png" alt="Dell G7 7588" width="40%">
</p>

This EFI repository contains the files needed to successfully boot into macOS on Dell G7 7588 with Opencore and Clover, also it's very stable now. macOS 12 Monterey works well with Windows 11 in dual boot, even with builtin UEFI Secure Boot with custom secure boot keys (currently OpenCore only). There are probably things that can be improved, so feel free to open issues or even PRs with suggestions or observations.

## Update

* Full changelog is here | [Changelog Archive](https://github.com/aksm-unmei/Dell-Inspiron-G7-7588-Hackintosh/blob/main/Changelog.md)

### Latest changelog

- Remove MMIO whitelist.
- Some optimisations.

## Guide

* For a more friendly reading experience, the guide is now hosted [here](https://aksm-unmei.github.io/hackintosh-guide/dell-g7/).

<h2>Thanks to</h2>

* [Acidanthera Team](https://github.com/acidanthera) for OpenCore Bootloader and many Kernel Extensions.
* [Juan-VC](https://github.com/Juan-VC/Hackintosh-macOS-Dell-G7-7588/blob/main/codec_dump.txt) for ALC256 codec dump.
* [black-dragon74](https://github.com/black-dragon74/ALCPlugFix-Swift) for ALCPlugFix-Swift.
* [profzei](https://github.com/profzei/Matebook-X-Pro-2018/wiki/Enable-BIOS-Secure-Boot-with-OpenCore) for UEFI Secure Boot and OpenCore guide.
* [daliansky](https://github.com/daliansky/OC-little) for ACPI patch snippets.

<h2>Support me</h2>

* [Paypal](https://www.paypal.me/tekun0lxrd)
