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
| 🔓 Unlock the phone | TODO: sound name | [▶️ Play](previews/unlock.mp3) |
| 🔒 Lock the phone | TODO: sound name | [▶️ Play](previews/lock.mp3) |
| 🪫 Low battery warning | TODO: sound name | [▶️ Play](previews/low-battery.mp3) |
| 🔌 Plug in the charger (wired / wireless) | TODO: sound name | [▶️ Play](previews/charging.mp3) |
| 👆 Touch / tap sounds | TODO: sound name | [▶️ Play](previews/touch.mp3) |
| 📸 Take a screenshot | TODO: sound name | [▶️ Play](previews/screenshot.mp3) |
| ⌨️ Keyboard key press (Gboard / AOSP keyboards) | TODO: sound name | [▶️ Play](previews/keyboard-key.mp3) |
| ⌨️ Keyboard space / delete / enter | TODO: sound name | [▶️ Play](previews/keyboard-space-delete.mp3) |
| ⚡ Power on (OneUI only, experimental) | TODO: sound name | [▶️ Play](previews/power-on.mp3) |

> **Note:** Samsung Keyboard keeps its sounds inside the app, so the keyboard sounds only work with Gboard or AOSP keyboards.

---

## 📦 Downloads

Get the zip for your device from the [**Releases**](../../releases) page.

| Version | For |
|---|---|
| `MinecraftUISounds_OneUI_v2.0.zip` | Samsung OneUI (including UN1CA) |
| `MinecraftUISounds_AOSP_v2.0.zip` | AOSP ROMs that use `/product/media/audio/ui` |

## 🛠️ Installation

1. Open **KernelSU** (or Magisk) → **Modules** → **Install**.
2. Select the zip for your device.
3. **Reboot.**
4. Make sure touch / system sounds are enabled in your sound settings.

To test the power-on sound, shut the phone down completely and start it with the power button. A normal restart usually doesn't play it.

## ❓ Troubleshooting

- **A sound didn't change:** check that the file exists on your device with
  `su -c ls /system/media/audio/ui/` (OneUI) or `su -c ls /product/media/audio/ui/` (AOSP).
- **OneUI sound themes:** pick the **Default** theme, otherwise the system may load the `_Calm` / `_Fun` / `_Retro` variants instead.
- **Installing an old version first?** Remove it, reboot, then install the new one.

## ⚠️ Disclaimer

This project is not affiliated with Mojang Studios or Microsoft. Minecraft and its sounds belong to their respective owners. Use this module for personal use only.
