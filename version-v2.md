# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.20
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.20.raucb
min_version: 1.2.6
size: 53475476

## Release Notes
- Adds support for wired Xbox controllers (Series X|S, One, 360) — they now show
  up as an input device on the transmitter.
- Transmitter RF settings read correctly from the phone (Telem Ratio + full
  option lists).
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
