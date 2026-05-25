# NESSO MARAUDER — Nesso N1 firmware

Official **pre-built firmware** for the Arduino **Nesso N1** (ESP32-C6).

## Download (flash files only)

**[Go to Releases → latest `Nesso_Marauder-x.y.z.zip`](https://github.com/maixent309/NessoSuite-Flash/releases)**

Each version is a separate release (1.0.2, 1.0.3, …). Unzip and run `flash_windows.bat`.

| File | Flash address |
|------|----------------|
| `bootloader.bin` | `0x00000` |
| `partition-table.bin` | `0x08000` |
| `firmware.bin` | `0x10000` |
| `ir_db.bin` | `0x310000` |

**Web UI:** WiFi **Nesso** / **nessonesso** → http://192.168.4.1

No source code in this repository.
