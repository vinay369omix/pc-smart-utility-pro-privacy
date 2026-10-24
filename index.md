# Privacy Policy — PC Smart Utility Pro (Omix Studios)

**Last updated: 24 October 2026**

## Summary

PC Smart Utility Pro has no accounts, no ads, no tracking and no analytics servers. Your PC information stays on your PC.

## What stays on your device

* System, hardware, network and security information shown in the app is read locally and is not uploaded by Omix Studios.
* Preferences, usage counters and any saved hardware baseline are stored locally on your PC. You can delete them by uninstalling the app or removing its data folder.
* The Duplicate File Finder reads the contents of files in folders you choose, only to compare them on your PC; file names and contents are never uploaded. Files you select are moved to the Recycle Bin.
* Similar Photos opens photos in folders you choose and makes a tiny 64×64 grey copy of each in memory to compare how alike they look. Fingerprints and thumbnails stay in memory on your PC until you close the app; nothing is uploaded or sent anywhere. Photos you select are only moved to the Recycle Bin. If you use Export, the list is saved only where you choose.
* Smart Uninstaller reads the list of installed programs from the standard Windows uninstall registry entries on your PC (read only) and starts the program's own uninstaller when you ask. Leftover search looks only for folders with the exact program name in AppData, ProgramData and Program Files, and only moves folders you tick to the Recycle Bin. The list is never uploaded; Export saves a CSV only where you choose.
* Reports, section notes, TXT snapshots and inventory CSV files are saved **only when you choose a location**. They may contain device details, so review them before sharing.

## Internet connections the app can make

1. **Connectivity check:** The Network section may request a small test file from `msftconnecttest.com` (Microsoft) to see whether you are online.
2. **Public IP lookup:** If you use that feature, the app requests your public IP address from `api.ipify.org`. That service sees your IP address, as any website does.
3. **Software Updater:** When you open it or click Check, the Windows Package Manager (winget, part of Windows, run by Microsoft) contacts its update sources to learn which of your installed apps have newer versions. To show a download size, the app asks the app vendor's download server for the file size; the file is not downloaded for this check. That server sees your IP address, as any website does. When you click Update, winget downloads the update from the vendor. Omix Studios does not receive any of this, and no list of your installed apps is sent to us.
4. **Omix AI model download:** Only if you choose to enable Omix AI, the app downloads one model file (Qwen2.5-0.5B-Instruct, about 490 MB) from `huggingface.co`. Hugging Face may log the request, such as your IP address, under its own policy.
5. **Links you click:** Microsoft Store and our website open in your browser and are governed by those sites' privacy policies.

## Omix AI (generative AI)

After the model is downloaded, everything you type to Omix AI is processed on your PC and is not sent online. Answers can be wrong; do not rely on them for medical, legal or security-critical decisions. Omix AI cannot run commands.

**Report this answer:** This opens an email draft to `omixstudios39@gmail.com` containing the question and answer. Nothing is sent unless you press Send.

## Administrator rights

The app runs as a normal user. Some Microsoft tools it can open, such as MRT.exe, may show Windows' own permission prompt.

## Children

The app is a general PC utility and is not directed at children.

## Changes and contact

We will update this page if the app's data handling changes.

**Contact:** `omixstudios39@gmail.com` — Omix Studios.
