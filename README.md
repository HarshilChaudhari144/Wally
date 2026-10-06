<div align="center">

# 🖼️ Wally

**Your wallpaper, on rotation.**

Put your photos into collections, set one for Home and one for the Lock Screen —
and let your wallpaper change itself.

_No ads · No account · Works fully offline_

</div>

---

## 📥 Install

| | |
|---|---|
| **1. Download** | Grab `wally-1.0.apk` from this repo |
| **2. Install** | Open it on your phone → allow **Install unknown apps** when asked |
| **3. Requires** | Android 7.0 or higher |

## ✨ Features

- 🗂️ **Collections** — group gallery photos into named collections
- 📱🔒 **Home + Lock targets** — different collections per screen, or one shared schedule for both
- ⏱️ **Your schedule** — per-collection intervals from 1 minute to 24 hours; survives reboots
- 🎬 **Videos** — clips play as muted, looping live wallpapers on Home; Lock Screen skips them gracefully
- ✂️ **Crop editor** — frame each photo per target (Home / Lock / Both), with rotate and small-image quality checks
- 🔀 **Ordering tools** — shuffle, drag to reorder, start-from-here, move to top / move to position
- 🛡️ **Respectful limits** — up to 100 collections and 500 prints each; over-cap flows always ask before removing anything

## 🔐 Permissions — and why each one exists

| Permission | Why |
|---|---|
| 🖼️ Media read access | To show your gallery and load wallpapers |
| 🎨 Set wallpaper | The whole point of the app |
| ⏰ Exact alarms + boot completed | Fire rotations on time, reschedule after restarts |
| 🔔 Notifications | A quiet note keeps rotation reliable on aggressive battery savers (exemption guidance in Settings) |

> **Privacy:** Wally has no network permission — nothing is uploaded, tracked, or synced.
> Your photos never leave your device. The only exception is the standard system
> cloud backup (your collections + settings, to your own Google account).

## 📝 Notes

- Everything is stored on-device — uninstalling removes your collections and settings.
- Live wallpapers go through the system picker, which has the final say on Home vs. Lock placement depending on your device.

---

<div align="center">

Built with Kotlin + Jetpack Compose · Designed and directed by a human, coded with AI assistance

**v1.0**

</div>
