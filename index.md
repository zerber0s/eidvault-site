---
layout: page
title: Privacy Policy
permalink: /
---

**Last Updated: April 9, 2026**

## Overview

EIDVault is a Windows® Event ID (EID) reference app built for iOS. It provides a searchable, offline-capable database of EIDs within Windows Event Log channels, including MITRE ATT&CK® mappings and investigation guidance.

**EIDVault does not collect, transmit, or share any personal information.**

---

## Information We Do Not Collect

EIDVault does not collect, store, or transmit:

- Your name, email address, or any contact information
- Your location
- Device identifiers (IDFA, IDFV, or similar)
- Usage analytics or behavioral tracking data
- Crash reports sent to external services
- Any form of personally identifiable information (PII)

There are no third-party analytics, advertising, or crash-reporting SDKs included in the app.

---

## Data Stored on Your Device

All data EIDVault stores remains entirely on your device and is never transmitted to any external server:

- **Event ID Database:** Windows Event ID reference entries sourced from bundled and remotely updated JSON files. This is reference data, not user data.
- **Favorites:** A boolean flag indicating which Event IDs you have bookmarked. Stored locally in the app's database.
- **Scenario History:** When you use the AI-powered investigation scenario feature, your query and the generated result are saved locally. Up to 50 scenario records are retained; older ones are automatically deleted. You can clear this history manually within the app.
- **Update Metadata:** Timestamps and version strings tracking when dataset files were last updated. Stored in iOS UserDefaults.
- **Spotlight Index:** Event ID reference data is indexed for iOS system-wide search. This index is device-local and managed by iOS.

---

## Network Requests

EIDVault makes outbound network requests solely to check for and download updated Event ID datasets. These requests are:

- **Anonymous HTTP GET requests** to `raw.githubusercontent.com` (GitHub's raw content CDN)
- **No user data is included** in these requests — they fetch publicly available JSON files only
- **User-initiated** via the "Check for Updates" control in the app, or performed in the background on launch

No other network communication occurs.

---

## Apple Intelligence / On-Device AI

EIDVault uses Apple's on-device FoundationModels framework (Apple Intelligence) to generate investigation scenarios. All AI inference runs **entirely on your device**. No query text, scenario output, or any other data is sent to Apple's servers or any other external service as part of this feature.

---

## Siri Shortcuts

EIDVault supports Siri Shortcuts via Apple's AppIntents framework. Any shortcuts you create operate locally on your device using the same on-device data. No user data is transmitted to external services as a result of Siri Shortcuts usage.

---

## External Links

EIDVault may display links to external websites, including MITRE ATT&CK (`attack.mitre.org`), Microsoft Learn (`learn.microsoft.com`), and GitHub (`github.com`). Tapping these links opens them in Safari. Once you leave the app, you are subject to the privacy policies of those third-party sites. EIDVault has no control over and assumes no responsibility for their content or practices.

---

## iCloud and Device Backups

EIDVault does not use iCloud or any cloud sync service. App data (your favorites, scenario history, and update metadata) may be included in your device's standard local or iCloud backup as part of normal iOS backup behavior. This is governed by your own Apple ID and backup settings.

---

## Children's Privacy

EIDVault is not directed at children under the age of 13 and does not knowingly collect any information from children.

---

## Changes to This Policy

If this privacy policy changes, the updated policy will be posted at this URL with a revised "Last Updated" date. Continued use of the app after changes are posted constitutes acceptance of the updated policy.

---

## Contact

If you have questions about this privacy policy, you can reach out at [eidvault@zerberos.io](mailto:eidvault@zerberos.io).
