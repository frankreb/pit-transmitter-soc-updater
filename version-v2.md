# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.1.0
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.1.0.raucb
min_version: 1.0.0
size: 53602452

## Release Notes
- First RAUC A/B OTA release — the device installs the signed .raucb into the
  inactive slot and reboots into it (automatic rollback if it fails to boot).
- Includes the "Update Transmitter SOC (V2)" flow in the PC app.
