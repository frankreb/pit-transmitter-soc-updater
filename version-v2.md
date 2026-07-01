# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.10
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.10.raucb
min_version: 1.2.6
size: 53467284

## Release Notes
- Fixes WiFi provisioning on 1.2.8/1.2.9 (a dangling /opt/pitlabs/networks
  symlink made the app report "connection failed" even though WiFi connected).
- WiFi settings continue to persist across updates (from 1.2.8 onward).
- Installs into the inactive A/B slot and reboots into it (automatic rollback
  if it fails to boot).
