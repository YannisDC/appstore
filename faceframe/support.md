---
title: Support
app: FaceFrame
---

Need help with {{ page.app }}? We’re happy to help.

## Contact us

Email us at **[{{ site.contact_email }}](mailto:{{ site.contact_email }}?subject={{ page.app | append: " support" | uri_escape }})**. We usually reply within 2 business days.

To help us solve your problem faster, please include:

- What happened, and what you expected to happen
- Your device model and iOS version
- Screenshots, if they help

## Frequently asked questions

### Which devices can scan?

Scanning uses the TrueDepth camera, so it needs an iPhone or iPad with Face ID. On other devices, tap **Try with a demo head** on the home screen to explore the measurements and the frame designer.

### How do I get a good scan?

- Take off glasses, earbuds and earrings.
- Tuck your hair behind your ears: the app must see where each ear meets your head.
- Use even, indirect light. Direct sunlight blinds the depth sensor.
- Hold the phone at eye level, about 30 cm away, and keep it still. Move your head, slowly.
- Turn the sound on: spoken instructions guide you while your head is turned.
- Keep a neutral expression with your mouth closed. Beards are fine.

The same tips are under **Tips for a good scan** on the home screen.

### A measurement looks wrong. Can I fix it?

Yes. On the review screen, tap the hand icon (**Adjust**), choose the landmark, and tap the model where it should be. Every value updates. **Reset to automatic** puts it back.

### Where are my files?

Open the **Files** app and go to **On My iPhone › FaceFrame › Scans**. Each saved scan has its own folder with its exports; the frames you export from the frame designer are in its **frames** folder.

### How do I 3D print the frames?

In the frame designer, choose **Export › Save all files for printing**. You get `frames.stl`, `lenses.stl`, `head.stl`, `frames.obj` and `design.json`, all in millimetres. Open `frames.stl` in your slicer or send it to a printing service. `head.stl` is handy to check the fit before printing.

### Can I check glasses I already own?

Yes, if you have a 3D model of them. In the frame designer, tap the glasses button at the top right and pick an `.obj` file from Files. The app shows where the pair touches or presses on your head.

### How do I delete a scan?

On the home screen, swipe left on the scan under **Your scans**, or touch and hold it, and tap **Delete**. This removes the scan, its head model, exports and frames from your device.

### Is my face scan uploaded anywhere?

No. Scanning, fitting and design all happen on your device, and {{ page.app }} has no network connection of its own. Your scan only leaves your device if you export or share files yourself. See our [privacy policy](../privacy/) for details.

### Can I use {{ page.app }} instead of an optician?

{{ page.app }} helps you design frames that fit your face. It is not a medical device and does not replace an eye examination or an optician’s fitting for prescription lenses.
