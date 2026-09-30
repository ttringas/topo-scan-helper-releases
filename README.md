# Topo Scan Helper — Downloads

Public distribution point for **Topo Scan Helper**, the macOS menu-bar app that sends
front-desk QR and barcode scans to Topo, even when the browser isn't in front.

The source code lives in a private repo. This repo holds the signed, notarized release
builds and the Sparkle auto-update feed (`appcast.xml`).

## Install on a front-desk Mac (one time)

1. **[Download the latest version](https://github.com/ttringas/topo-scan-helper-releases/releases/latest/download/Topo-Scan-Helper.dmg)**
2. Open the downloaded `Topo-Scan-Helper.dmg`, drag **Topo Scan Helper** onto
   **Applications**, then eject the disk image.
3. Open **Topo Scan Helper** from Applications. It opens with no warning (the app is
   signed and notarized by Apple).
4. When macOS asks, grant **Accessibility** permission.
5. In Topo, open **Scanner workstations**, add this desk, and click its setup link.
   The link fills in your gym and the desk's token automatically.
6. On the Check-In page, pair the desk's browser from the footer
   (**Pair this browser**).
7. The first time a scan needs the browser, click **OK** when macOS asks to let the
   app **control Google Chrome**.
8. From the menu-bar icon, turn on **Launch at Login**.

## Updates are automatic

The app checks for updates in the background and installs them itself; desks update
within an hour of a release. The menu's **Check for Updates…** forces a check, and the
**Version** line shows what's installed.
