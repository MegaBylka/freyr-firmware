# Freyr firmware releases

This repository holds only the release files of the Freyr firmware: `firmware.bin`, `littlefs.bin` (user interface) and `manifest.json`.

- Every file is signed (ECDSA P-256). Devices install only images signed with the Freyr release key and verify them before switching.
- Devices read `releases/latest/download/manifest.json` and offer the update; nothing is installed without a request on the device.
- Versions follow `major.minor.patch`.

The source code is not published here.
