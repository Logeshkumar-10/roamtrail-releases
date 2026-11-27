<p align="center"><img src="logo.png" width="128" alt="RoamTrail logo"></p>

# RoamTrail

A personal travel tracker for Android. RoamTrail records where you go, clears a fog map along your path, and shows how much of each city you track you have covered. Your history stays on your phone, and you can back it up to your own OneDrive or Google Drive.

<!-- Hero image goes here (release phase R3). -->

This page has the app's downloads, release notes and privacy policy. The app is not on Google Play.

**For ages 18 and over.** The terms of service are shown in the app, on the first screen and in Settings > About. Starting the app means you agree to them.

## What it does

- **Fog map:** clears along the path you travel, in a choice of map styles.
- **Journeys:** driving, walking and train or metro, with your vehicle or as a passenger (bus, taxi, other). The guess can be wrong, and you can correct it.
- **Cities:** add a city and see how much of its roads and railway lines you have covered. You can draw or edit its boundary.
- **Heat and home zones:** see which roads you use most; home zones stay hidden from it.
- **Timeline:** by day, month, year, all time or chosen dates, with route replay and saved trips.
- **Fuel log:** fills, mileage and cost per km, with receipt scanning on the phone.
- **Vehicles:** keep several, each with its own stats.
- **Your data:** export it or delete it in Settings > Storage.
- **Languages:** English, Tamil and Hindi, with light and dark themes.

<!-- Screenshots go here (release phase R3). -->

## Install

1. Open **[Releases](../../releases/latest)** on your Android phone and download `RoamTrail-<version>.apk`.
2. Open the downloaded file. If Android asks, allow your browser or file manager to **install unknown apps**.
3. Google Play Protect may warn you or offer to scan the app, because it is not from the Play Store. See [Troubleshooting](#troubleshooting).
4. Open RoamTrail and follow the four setup screens. Nothing is recorded until you tap **Start tracking**.

Android 7.0 or newer is needed. The download is large (about 185 MB) because one file holds the app for every kind of phone processor.

## Update

Download the newer APK from Releases and install it over the old one. Your trips and settings are kept.

## Troubleshooting

Screens and button names differ between Android versions and phone brands.

- **"Install unknown apps":** Android blocks installs from a browser or file manager until you allow it. When the message appears, open the settings it offers, turn the permission on for that app, then open the APK again. You can turn it off afterwards.
- **Play Protect warning:** Play Protect may say it has not seen this app before, with the choices **Scan app** and **Don't install app**. Choose **Scan app** and follow the result. Only install a file downloaded from this page.
- **Recording stops by itself:** some phone brands stop apps to save battery. In RoamTrail, open Settings > Tracking, use **Open battery settings** or **Open app settings**, and let RoamTrail run in the background. Some brands add extra switches, for example Autostart or Sleeping apps.
- **Nothing is recorded:** check that location access is **Allow all the time** and that you tapped **Start tracking**.

## Version history

| Version | Date        | What changed                                                         | Size   | Checked on a phone          |
| ------- | ----------- | -------------------------------------------------------------------- | ------ | --------------------------- |
| 0.1.4   | 26 Nov 2026 | Terms of service and an updated privacy policy.                      | 185 MB | No, PC only                 |
| 0.1.3   | 26 Nov 2026 | Map, timeline and typing fixes; cost per km on Fuel.                 | 185 MB | No, PC and partly emulators |
| 0.1.2   | 25 Nov 2026 | Start without a vehicle; replay and trip changes; backup fixes.      | 185 MB | No, PC only                 |
| 0.1.1   | 24 Nov 2026 | First public download; fixes a crash at start and Microsoft sign-in. | 185 MB | Yes, Pixel 7 Pro            |

Full notes for each version are under [Releases](../../releases).

## Check your download

Each release page shows the SHA-256 of its APK. To compare on Windows, run this in PowerShell, in the folder with the file:

```powershell
Get-FileHash .\RoamTrail-0.1.4.apk -Algorithm SHA256
```

The result must match the line for your version (capital or small letters do not matter):

```text
eaea53f5971ec511e580bc40207a14aa5595009e6edc050ba77dc59ab4665c9d  RoamTrail-0.1.4.apk
859b009861bec2fee91a4a07d5a3307c83941a7187b9708d7786679dabae8d1e  RoamTrail-0.1.3.apk
3750c41f2c72b3f7a3b0c9d3adc5d4156f90648ffae5bc08d5e9c895fc8a737b  RoamTrail-0.1.2.apk
b9a1b58e1a2979dc4f60385da43e1a26012e1d5860b9977dcfd50e22bc80a262  RoamTrail-0.1.1.apk
```

For a newer version, use the checksum on its release page.

## Good to know

- **Location:** the app needs location access set to **Allow all the time** to record while the phone is locked. It shows a small notification while recording.
- **Battery:** some phone brands stop background apps. The app's Settings > Tracking explains what to change.
- **Backup:**
  - Microsoft accounts can back up to OneDrive.
  - Google Drive backup currently works only for accounts the developer has added, because the Google sign-in is still in testing.
  - Without a backup, everything stays on the phone only.
- **Map data:** © OpenStreetMap contributors (ODbL). Map tiles by OpenFreeMap © OpenMapTiles.
- **Also used:** OpenStreetMap Nominatim and Overpass, MapLibre, Google ML Kit, the Inter and Plus Jakarta Sans fonts (SIL OFL 1.1), Tabler Icons (MIT) and Material Design Icons (Apache 2.0). All library licences are listed in the app under Settings > About.

## Privacy

There is no RoamTrail server, and RoamTrail adds no analytics or advertising. Google ML Kit, used to read receipts, sends diagnostics to Google. Read the full **[privacy policy](PRIVACY.md)**.

<!-- Links to website pages go here (release phase R5). -->

## Contact

Logeshkumar Sivakumar · elogu2001@outlook.com
