# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.7
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.7.raucb
min_version: 1.2.6
size: 53463188

## Release Notes
- First OTA that actually reaches GitHub over HTTPS (the image now builds
  Python with SSL).
- Update the transmitter firmware from the phone ("Update from your phone") or
  the PC app ("Update Transmitter SOC (V2)").
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
