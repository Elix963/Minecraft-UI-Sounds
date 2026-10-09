<div align="center">

# ⛏️ Minecraft UI Sounds

**Replace your phone's system sounds with Minecraft sounds.**
A root module for KernelSU / Magisk — lock, unlock, charging, screenshot and more.

![Root](https://img.shields.io/badge/root-KernelSU%20%7C%20Magisk-green)
![Android](https://img.shields.io/badge/Android-AOSP%20%7C%20OneUI-blue)
![Version](https://img.shields.io/badge/version-2.0-orange)

</div>

---

## 🎧 Sound list

Click **▶️ Play** to listen before you install.

| What triggers it | Minecraft sound | Preview |
|---|---|---|
| 🔓 Unlock the phone | Chest open | [▶️ Play](previews/unlock.mp3) |
| 🔒 Lock the phone | Chest closed | [▶️ Play](previews/lock.mp3) |
| 🪫 Low battery warning | Hit sound | [▶️ Play](previews/low-battery.mp3) |
| 🔌 Plug in the charger (wired / wireless) | Xp sound | [▶️ Play](previews/charging.mp3) |
| 👆 Touch / tap sounds | Minecraft menu click sound | [▶️ Play](previews/touch.mp3) |
| 📸 Take a screenshot | villager sound | [▶️ Play](previews/screenshot.mp3) |
| ⌨️ Keyboard key press (Gboard / AOSP keyboards) | Item drop sound | [▶️ Play](previews/keyboard-key.mp3) |
| ⌨️ Keyboard space / delete / enter | Hit sound | [▶️ Play](previews/keyboard-space-delete.mp3) |
| ⚡ Power on (OneUI only, experimental) | achievement | [▶️ Play](previews/power-on.mp3) |

> **Note:** Samsung Keyboard keeps its sounds inside the app, so the keyboard sounds only work with Gboard or AOSP keyboards.

---

## 📦 Downloads

Get the zip for your device from the [**Releases**](../../releases) page.

| Version | For |
|---|---|
| `MinecraftUISounds_OneUI_v2.0.zip` | Samsung OneUI `/system/media/audio/ui` |
| `MinecraftUISounds_AOSP_v2.0.zip` | AOSP ROMs `/product/media/audio/ui` |

## 🛠️ Installation

1. Open **KernelSU** (or Magisk) → **Modules** → **Install**.
2. Select the zip for your device.
3. **Reboot.**
4. Make sure touch / system sounds are enabled in your sound settings.

To test the power-on sound, shut the phone down completely and start it with the power button. A normal restart usually doesn't play it.

## ❓ Troubleshooting

- [Tested on OneUI 8]
  
- **OneUI sound themes:** Go to **Sittings** → **Sounds and vibration** → **System sound** → **System sound theme** and pick the **Default** theme, Otherwise, the sounds will not work.

## ⚠️ Disclaimer

**Use this module at your own risk.**

This module is provided "as is", without warranty of any kind. I am **not responsible** for any damage to your device, including but not limited to:

- Bootloops or soft-bricks
- Data loss
- Audio, system or app malfunctions
- Warranty loss, or any other issue caused by rooting or flashing modules

By installing it you accept full responsibility. Always make a backup first, and make sure you know how to disable or remove KernelSU / Magisk modules (for example from recovery or safe mode) if something goes wrong.
