# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.9
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.9.raucb
min_version: 1.2.6
size: 53463188

## Release Notes
- Test release to confirm WiFi settings persist across an update. Coming from
  1.2.8 (or later), the transmitter should keep its WiFi with no re-provisioning.
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
