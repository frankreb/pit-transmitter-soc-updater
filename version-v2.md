# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.17
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.17.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Fixes "rauc install failed" on the read-only root: firmware updates now mount
  under /run (tmpfs) instead of the read-only /mnt, so installs work from both
  the PC app and the phone without any workaround.
- Together with 1.2.16 (child-signal fix) this completes the phone update flow:
  it now downloads, installs, activates the new slot, and reboots into it.
- WiFi/config live on /data and are preserved across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
