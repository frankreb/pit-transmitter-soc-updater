# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.12
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.12.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Root filesystem is now read-only during operation (remounted read-only at the
  end of boot), so an abrupt power-off can no longer corrupt it — preventing the
  ext4 boot kernel panics. All settings/config/WiFi keep working (they live on
  the separate /data partition).
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
