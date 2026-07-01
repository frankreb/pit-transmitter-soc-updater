# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.6
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.6.raucb
min_version: 1.2.5
size: 53598356

## Release Notes
- Adds "Update Transmitter SOC (V2)" from the mobile app — update the
  transmitter's firmware directly from your phone, no computer needed.
- The firmware version now tracks the sim-to-rc app version.
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
