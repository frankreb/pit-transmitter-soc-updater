# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.11
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.11.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Groundwork for a read-only rootfs: writable state (WiFi, saved networks, app
  config, provisioning) now uses baked symlinks to /data seeded from read-only
  defaults; Qt HOME is on tmpfs. No behaviour change on the current read-write
  root — your WiFi + config carry over untouched.
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
