# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.8
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.8.raucb
min_version: 1.2.6
size: 53467284

## Release Notes
- WiFi settings + saved networks now survive firmware updates (persisted on the
  /data partition). Note: updating FROM a version before 1.2.8 re-provisions
  WiFi once; from 1.2.8 onward it carries over automatically.
- App config / profiles / presets already persisted and continue to.
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
