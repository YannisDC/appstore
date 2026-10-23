---
title: Privacy Policy
app: FaceFrame
updated: 2026-10-23
---

{{ page.app }} is committed to protecting your privacy. This policy explains how {{ site.company }} (“we”, “us”) handles information in the app. In short: {{ page.app }} processes your face scan entirely on your device to fit glasses. We do not collect, store, or transmit any personal information, including face data, to our servers or to third parties. {{ page.app }} has no account, no analytics, no advertising and no network connection of its own.

## Information we do not collect

{{ page.app }} does not collect, store, or transmit the following to our servers or third parties:

- Personal information (name, address, email, phone number, etc.)
- Face scans, face data or any derived measurements
- Photos or camera images
- Usage analytics or tracking data
- Device identifiers or advertising IDs
- Location data
- Any data about how you use the app

## Face data

{{ page.app }} uses the TrueDepth camera and Apple’s ARKit face tracking to build a 3D model of your head and measure where glasses will sit. This section explains what face data the app uses, why, and what happens to it.

### What face data the app uses

While you scan, the app uses:

- **Depth frames** from the TrueDepth camera
- **Head position and face geometry** from ARKit face tracking, including the position of your eyes
- **A few colour frames** from the camera (a front view and one turned view to each side), on which facial landmarks, the outline of your head and your ears are detected

From these, the app computes a **3D model of your head**, a **fitted head model** (a set of shape parameters for a 3D head model) and **measurements** used for glasses, such as your pupillary distance, the shape of your nose and the position of your ears.

### How face data is used

Face data is used only to build the 3D model of your head, measure it, and design and fit glasses frames to it. It is not used for identification, authentication, advertising, marketing, profiling, or any purpose other than the app’s glasses-fitting features.

### Where face data is processed

All processing happens **on your device**, including the face and ear detection models, which are bundled with the app. No face data is sent to us, to Apple, or to any third party.

### Sharing

We do not share face data with anyone. Face data only leaves your device if you choose to export or share files yourself (see [Exporting and sharing files](#exporting-and-sharing-files)).

### Retention

- **Depth and colour frames** are kept in memory during the scan and discarded once the scan is processed, unless you turn on *Record raw capture* (see below).
- **Saved scans** (the 3D model of your head, the fitted head model and the measurements) are stored on your device only when you choose to save a scan, and are kept until you delete them.
- **Exported files** stay where you save them until you delete them.

## Data stored on your device

### Saved scans

When you save a scan, the 3D model of your head, the fitted head model, your measurements and any landmark adjustments are stored in the app’s folder on your device. They appear in the Files app under FaceFrame. You can delete a saved scan from the app at any time.

### Recorded captures

If you turn on *Record raw capture* in the app, the next scans also store every depth frame, the head positions and some colour images of your face on your device, so the scan can be replayed later. This option is off by default. You can delete recorded captures in the Files app under FaceFrame › Captures.

### Head model preferences

You can optionally choose a sex and an ethnicity group so the head model starts from typical shapes for that group. This choice is stored only in the app’s settings on your device, used only to fit the head model, and never transmitted. You can reset it to “Not set” at any time.

### Device backups

Files stored by the app may be included in your device backups (for example iCloud Backup or a backup to your computer), according to your device settings. These backups are handled by Apple or by you and are subject to Apple’s privacy policies. We do not have access to them.

## Permissions

### Camera

The app asks for camera access to scan your head with the TrueDepth camera. The camera is only used while you are scanning, never in the background. You can revoke this permission at any time in your device’s Settings app. Without it, you can still use the demo head and open saved scans.

## Exporting and sharing files

You can export 3D files (for example STL, PLY and OBJ files of your head and of the frames), your measurements, and recorded captures, and share them through iOS sharing features. When you do, the files are saved or sent directly from your device to the destination you choose (e.g. Files, AirDrop, Messages, Mail, or a 3D printing app). Exported files can contain your face data. We do not facilitate or have access to these transfers.

You can also open a 3D model of an existing pair of glasses from the Files app to try it on. The file is only read on your device.

## Third-party services

The app uses the following Apple frameworks, which run on your device and are subject to [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/):

- **ARKit** – face tracking during the scan
- **Vision and Core ML** – detection of face landmarks, the outline of your head and your ears in the colour frames
- **App Store** – app distribution

The app also includes a 3D head model based on GNM (Apache 2.0) and face landmark, ear landmark and segmentation models (BSD-3 and Apache 2.0). They run entirely on your device and do not send any data.

We do not use any third-party analytics, advertising, or tracking services.

## Children

{{ page.app }} is not intended for children under 13. We do not knowingly collect personal information from children. If you believe we have inadvertently collected information from a child, please contact us and we will take steps to address it.

## Security

Since all your data is stored on your device, its security is mainly provided by iOS and your device settings. We recommend using a passcode or Face ID, keeping iOS up to date, and being careful with whom you share exported scans, since they contain a 3D model of your face.

## Your rights

You have full control over your data:

- **Delete data:** delete saved scans in the app, and any of the app’s files (scans, exports, frames, recorded captures) in the Files app
- **Stop recording:** turn off *Record raw capture* at any time
- **Revoke permissions:** turn off camera access in your device’s Settings app
- **Uninstall:** uninstalling the app removes all data it stored on your device (files you exported elsewhere and device backups remain)

Depending on where you live, including the EU, the UK and California, you may have further rights over your personal data. Since we hold none, there is nothing for us to access, correct or delete, but you’re welcome to contact us with any question.

## Changes to this policy

We may update this policy to reflect changes in our practices or legal requirements. When we do, we’ll change the date at the top of this page. Significant changes will also be announced in the app or its App Store listing.

## Contact

If you have questions about this policy or our privacy practices, contact Yannis De Cleene at {{ site.company }}: [{{ site.contact_email }}](mailto:{{ site.contact_email }}).

This policy is designed to comply with Apple’s App Store Review Guidelines (including the requirements for apps that use face data), the GDPR, the CCPA and other applicable privacy laws.
