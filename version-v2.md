# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.15
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.15.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Test build for the phone "Update Transmitter SOC (V2)" flow.
- Read-only root + SSH-on-read-only fix carried forward. Settings/WiFi live on
  the /data partition and are preserved across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
