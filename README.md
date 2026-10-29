# Xurco Spoofer

An iPhone location-simulation app customized for Xurco. Map search, coordinate selection, bookmarks, pairing-file import, local developer tunnel and restore-real-location controls.

## Origin and license
This is a modified derivative of TLocation (https://github.com/truongkma/t-location), based on upstream commit 5e57f815e5958f133dfbaae8252473054adeccf0, which derives its device engine from StikDebug by Stephen Bove and contributors. Apple-device communication uses idevice by jkcoxson. Original copyright notices and AGPL-3.0 license are retained. This is not affiliated with Roam Control or Vanish.

Changes: Xurco Spoofer branding, independent bundle identifier and URL scheme, purple accent, visible credits, and a dedicated unsigned IPA cloud build. Existing upstream location and connection behavior is retained. iOS 27.2 device compatibility has not yet been verified.

## Build and install from Windows
GitHub Actions builds the native app on macOS. Download Xurco-Spoofer-iPhone from the successful workflow, extract Xurco-Spoofer.ipa, and sign/install it using your existing SideStore or compatible sideloading setup. The build artifact is unsigned; it cannot be installed just by tapping it in Files.

Import the device's RP pairing file inside the app, enable LocalDevVPN and Developer Mode, and connect to Wi-Fi before starting the connection. Keep pairing records private. Use Return to Real Location to stop simulation. A new pairing record may be needed after an iOS update.

The complete modified source is this repository. See LICENSE for AGPL-3.0 terms. No Apple ID, private pairing file or signing credentials are required in the cloud build.
