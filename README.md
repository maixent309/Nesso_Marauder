# NESSO SUITE — Nesso N1 firmware

Official **pre-built firmware** for the Arduino **Nesso N1** (ESP32-C6).

## Download (flash files only)

**[Go to Releases → download the latest `NESSO-N1-x.y.z.zip`](https://github.com/maixent309/NessoSuite-Flash/releases)**

Each ZIP includes:

| File | Flash address |
|------|----------------|
| `bootloader.bin` | `0x00000` |
| `partition-table.bin` | `0x08000` |
| `firmware.bin` | `0x10000` |
| `ir_db.bin` | `0x310000` |

Plus `flash_windows.bat`, `flash.sh`, and `FLASH_INSTRUCTIONS.txt`.

### Quick flash (Windows)

1. `pip install esptool`
2. Unzip the release
3. Double-click `flash_windows.bat` (or `flash_windows.bat COM3` for another port)

### After flash

- On-device: **Device → About** shows the version
- Web control: WiFi **Nesso** / **nessonesso** → http://192.168.4.1

---

This repository contains **no source code** — only release packages.  
Firmware development is private.

Use only on networks you own or with written permission.
