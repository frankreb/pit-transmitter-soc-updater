# PIT SimBridge Firmware — RAUC A/B (V2)

latest: 1.2.28
bundle: https://raw.githubusercontent.com/frankreb/pit-transmitter-soc-updater/master/pit-simbridge-1.2.28.raucb
min_version: 1.2.6
size: 53868692

## Release Notes
- Receiver mode: switch the PIT Receiver between car and helicopter from the
  app, over ELRS (receiver firmware 4.5.3 / 1.9.2) or with the cable.
- Race control: one phone controls every station — stop all, pit limiter,
  speed cap and reverse per car, and a safety link that stops the car if race
  control goes quiet.
- Steering angle (240°, 360°, 540°, 900° or the full wheel), a steering check
  while transmitting, and FFB settings saved with the profile and as presets.
- HUD speed tuning per car (top speed, acceleration, braking).
- WiFi update mode on purpose for the transmitter's radio and the PIT
  Receiver; they no longer switch to WiFi by themselves (needs transmitter
  MCU firmware 1.3.7).
- Wheel force feedback and motion rig output (SimHub / FlyPT / SimTools) from
  the PIT receiver V4 car telemetry; PIT receiver settings, GPS status and
  gyro calibration over ELRS.
- The phone app reconnects by itself when the connection drops.
- Your Wi-Fi and settings are kept across the update.
- Installs into the inactive A/B slot and reboots into it (automatic rollback if
  it fails to boot).
