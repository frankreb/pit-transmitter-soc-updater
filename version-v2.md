# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.21
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.21.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Xbox controller buttons and sticks can now be assigned in the phone app —
  previously the controller was detected but no input could be mapped.
- If you had button assignments on a device that mixes several button types
  (e.g. a wheel with extra shifter buttons), double-check them after updating.
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
