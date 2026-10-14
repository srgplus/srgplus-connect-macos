# SRG+ Connect for Mac

The Mac app of SRG+ Connect, for download outside the App Store. **Dev build, for the studio's own testing:** it talks to
the Dev server of SRG+ Connect and signs in with the SRG+ dev account.

**Download:** [SRG-Plus-Connect.dmg](https://github.com/srgplus/srgplus-connect-macos/releases/latest/download/SRG-Plus-Connect.dmg)

Open the DMG and drag SRG+ Connect to Applications. The app updates itself (Sparkle): it checks once a day, and
**SRG+ Connect › Check for Updates…** checks at once. It needs macOS 26 or later.

This repository only hosts the releases (the DMG) and `appcast.xml`, the update feed the installed apps read
(GitHub Pages, `https://srgplus.github.io/srgplus-connect-macos/appcast.xml`). The app's code and the build script
(`apps/apple/scripts/mac-dmg.sh`) are in the private repository srgplus/srgplus-connect. Changes to `appcast.xml` go
through a pull request, never straight to `main`.
