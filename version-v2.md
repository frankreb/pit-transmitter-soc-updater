# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.25
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.25.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Fixes device authorization giving up too early at boot: the app now waits
  for the full authorization retry schedule instead of exiting after the
  first failed attempt, so units with slow Wi-Fi or clock sync at power-on
  authorize reliably.
- Includes the recent fixes: startup on newer transmitter hardware revisions
  (1.2.23) and Xbox controller support (1.2.21/1.2.22).
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
