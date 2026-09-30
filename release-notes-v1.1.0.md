# AIM Joystick Probe v1.1.0

## What's new

- **See activity on every device.** The sidebar now watches all your
  controllers, not just the one you have selected. Press a button, move a hat
  or move an axis on any device and its row lights a green dot with a badge
  naming the input, such as **Btn 37** or **Axis 2**. With a crowded setup, you
  can press a control and see straight away which device it belongs to.
  ([#2](https://github.com/invictuscockpits/AIM-Joystick-Probe-Releases/issues/2))

## Fixes

- **Button-only and axis-only devices now show up.** Controllers that report
  only buttons (such as the Moza FMP18 DDI bezels) or only axes (such as
  Saitek Combat Rudder Pedals) were missing from the device list, even though
  Windows and your sims saw them. The Probe now uses a newer controller
  library that detects them.
  ([#1](https://github.com/invictuscockpits/AIM-Joystick-Probe-Releases/issues/1))
- Devices without enough axes for the X / Y pad no longer show an empty pad.
- Long device names no longer push the header controls off the edge of the
  window.

Thanks to @djfergus for reporting both issues and testing the fix on real
hardware.

## Install

Download **AIM-Joystick-Probe-v1.1.0-Setup.exe** below and run it. It installs
over your existing copy and keeps your settings. The installer and the app are
code-signed by Invictus Machine LLC, and it installs per-user with no
administrator rights needed.

## Documentation

Full guide is on the [wiki](https://github.com/invictuscockpits/aim-joystick-probe-releases/wiki).
