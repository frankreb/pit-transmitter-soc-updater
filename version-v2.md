# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.19
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.19.raucb
min_version: 1.2.6
size: 53471380

## Release Notes
- Transmitter RF settings now read correctly from the phone — fixes Telem Ratio
  and other long options that could show the wrong value or a short list.
- Configure-then-confirm flow: RF changes are staged and applied together, then
  the module restarts to apply them.
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
