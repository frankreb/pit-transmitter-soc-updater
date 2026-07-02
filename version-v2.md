# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.13
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.13.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Fixes SSH on the read-only root: the transmitter's SSH host keys now live on
  the /data partition, so they're writable and persist across updates (stable
  host key). Previously SSH could drop the connection after the read-only change.
- Root filesystem stays read-only during operation (power-cut corruption / boot
  panic protection). All settings/config/WiFi live on /data.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
