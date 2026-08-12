# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.23
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.23.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Fixes a startup failure on newer transmitter hardware revisions (unit would
  never finish powering on). Already-working transmitters are unaffected — for
  them this update just keeps the firmware version current.
- Includes the Xbox controller fixes from 1.2.21/1.2.22 (buttons and sticks
  assignable in the phone app; reliable controller start at power-on).
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
