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
