# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.18
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.18.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Zero-touch phone update test. From 1.2.17 (which has both the child-signal and
  rauc mount-prefix fixes), updating from the phone should just work: download,
  install, activate the new slot, and reboot — no console, no workaround.
- WiFi/config live on /data and are preserved across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
