# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.22
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.22.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Xbox controllers now start up reliably: previously, powering the transmitter
  on with a controller plugged in could leave it stuck with a blinking logo and
  no working inputs until it was re-plugged.
- Includes the 1.2.21 fix: Xbox controller buttons and sticks can be assigned
  in the phone app.
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
