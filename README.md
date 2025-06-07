# Metrolist (Aqua Dynamics Spoofed Spotify Package)
---


## 🚨 Important:
- Read This Entire README Before Installing.
- This is only for users who are NOT using Spotify and want to use an Open-Source Alternative but miss the Aqua Dynamics functionality with music a app on ColorOS or OxygenOS without root. 



This is a **modified version of Metrolist** (GPLv3) with a **spoofed package name (`com.spotify.music`)** to **trigger Aqua Dynamics 2.0 (aka Dynamic Island)** on devices running **ColorOS 15 and OxygenOS 15**.

- Everything else in the app is untouched.  
- No Spotify functionality is included or imitated.

---

## What This Does

- Spoofs package to `com.spotify.music`.
- Unlocks Aqua Dynamics animations when music plays.
- App icon and name are not changed.
- All functionality still comes from original Metrolist.

---

##  Requirements

- Android with **ColorOS 15** or **OxygenOS 15**.
- Uninstall real Spotify (if installed).
- Disable **auto-updates** for Spotify on Play Store.

---

## How to Install

1. Go to the **[Releases](https://github.com/KarthikeyaSarvan/metrolist-dynamic-island/releases)** tab.
2. Download the latest `metrolist-spotify.apk`.
3. Install using your file manager.
4. If you get a **Play Protect warning**, tap:
   > **More details → Install anyway**

---

## Warnings

- **Do NOT install the real Spotify app** — it shares the same package name and will overwrite this app or cause issues.
- Go to Play Store → Spotify → ⋮ menu → **Disable auto-updates**.
- This APK only changes **package and label names** — no functional changes were made.
- If the app crashes or doesn’t behave as expected, **report it to the original Metrolist repo**, not here.

🔗 Report bugs: [https://github.com/mostafa-saad/Metrolist/issues](https://github.com/mostafaalagamy/Metrolist/issues).

---

## File Contents

- `AndroidManifest.xml` – Modified for `com.spotify.music`.
- `metrolist-spotify.apk` – Rebuilt and signed APK.
- `LICENSE` – GPL v3.0 from the original repo.
- `README.md` – This file.

---

## How It Was Built (Technical Details)

1. Decompiled with `apktool_2.11.1.jar`.
2. Renamed all `com.metrolist.music` to `com.spotify.music`.
3. Modified `AndroidManifest.xml` and smali files.
4. Rebuilt with `apktool`.
5. Signed with `uber-apk-signer-1.3.0.jar`.

---

## License

This repo complies with the [GNU GPL v3.0 license](https://www.gnu.org/licenses/gpl-3.0.html), as used by the original Metrolist:

> Original Project: [Metrolist on GitHub](https://github.com/mostafaalagamy/Metrolist)

This modified release only alters package metadata to support certain OEM features — **all credit** goes to the original developers.

---

## Disclaimer

This is a **community modification**:
- Not affiliated with Spotify or Metrolist's original developer.
- Shared purely for educational and personalization use.
- Use at your own discretion and risk.
