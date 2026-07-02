# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.16
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.16.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Fixes the phone ("Update from your phone") update never actually switching to
  the new firmware. The updater now resets its child-signal handling so the A/B
  slot activation works regardless of whether the update was started from the PC
  app or the phone.
- Read-only root + SSH-on-read-only fixes carried forward. WiFi/config live on
  /data and are preserved across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
