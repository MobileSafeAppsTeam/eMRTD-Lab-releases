# eMRTD Lab — Releases

Public download mirror for **eMRTD Lab**, an NFC electronic-ID (eMRTD / eID)
**emulator and reader** built as a developer & QA testing tool.

> The application source code is maintained in a private repository. This repo
> only hosts the signed release APKs.

## Download

Grab the latest signed APK from the [**Releases**](../../releases) page and
install it on an NFC-capable Android device. You may need to allow installation
from unknown sources.

Each release asset is named `eMRTD-Lab-<version>.apk`.

Installing a new APK over an existing install keeps your data, as long as it is
the same signed build (it always is, for official releases here).

## Automatic updates (Obtainium)

Since this app is distributed outside Google Play, it does not auto-update on its
own. The easiest way to get update notifications and one-tap installs is
[**Obtainium**](https://github.com/ImranR98/Obtainium) — an open-source app that
tracks GitHub releases:

1. Install Obtainium.
2. Add an app and paste this repository's URL:
   `https://github.com/MobileSafeAppsTeam/eMRTD-Lab-releases`
3. Obtainium will notify you of new releases and install them for you.

You can also tap **Check for updates** inside the app (About dialog): it checks
this repo and points you to the latest release.

## What it does

- Emulates an eMRTD / CIE contactless chip over Android HCE (Host Card Emulation).
- Reads real eID/eMRTD chips and shows a live APDU log.
- Implements the standard protocol stack for realistic testing: **BAC**, **PACE**
  (NIST & Brainpool curves, AES), **Secure Messaging**, **Active Authentication**,
  **Chip Authentication**, Passive Authentication (EF.SOD), and the Italian
  **IAS-ECC** applet flows.

## Intended use

This is a **testing and development tool** for engineers and QA working with
NFC electronic-identity protocols. It is **not** affiliated with, endorsed by, or
connected to any government, issuing authority, or document-producing body, and it
does not read, store, or transmit data from genuine identity documents to any
third party. Use it only on documents and credentials you are authorized to test.

## Privacy & Terms

- Privacy policy: <https://mobilesafeapps.github.io/privacy?app=eMRTD%20Lab>
- Terms & conditions: <https://mobilesafeapps.github.io/terms?app=eMRTD%20Lab>

## Support

Questions or issues: **mobilesafeapps@gmail.com**
