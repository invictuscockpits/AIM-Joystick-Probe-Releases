# Changelog

All notable changes to AIM Joystick Probe are documented here.

## 1.2.0 (2026-10-03)

### New

- **Axis quality:** travel and full range (✓), noise, effective resolution
  in bits, and a History graph of one or all axes
- **Real axis names** from the device (AIM Ghost axes 7 and 8 are the Dial
  and the Slider)
- **X / Y trail** and a **Centering** card (rest points magnified 10x, with
  spread and offset)
- **Event log** with **switch bounce** detection; Test all covers axes
- **Report rate** in Hz; **identical devices** numbered
- **Force feedback and rumble test** (experimental)
- **Save snapshot** (choosable folder) and **Copy diagnostics**
- **Settings** gear, collapsible cards, and an info icon on every card
- Installer shows the license agreement and ships third-party notices

### Changed

- License: free for personal or commercial use; unmodified copies may be
  shared and redistributed free of charge
- Bundled Montserrat and JetBrains Mono fonts
- The X / Y dot shows the true reading, without smoothing

### Fixed

- Axis noise on devices that roll over end to end; resolution on
  high-resolution devices
- "-0.00" in readouts

## 1.1.0 (2026-09-30)

### New

- **Activity on every device:** the sidebar lights a green dot and a badge
  (Btn, Hat or Axis) on any device you touch, even when it isn't selected

### Fixed

- Button-only devices (such as Moza FMP18 DDIs) and axis-only devices (such as
  Saitek Combat Rudder Pedals) now appear in the device list
- The X / Y pad is hidden on devices with fewer than two axes
- Long device names no longer push the header controls off screen

## 1.0.0 (2026-06-29)

First public release.

### Highlights

- **Full button map:** all 128 buttons, live, with no 32-button cap
- **X / Y axis pad** with a live position dot
- **Axes and POV hats** with familiar Windows-panel names
- **Test-All mode:** latches each button as you press it, with a tested count
- **Last-pressed and held-count** readouts for stuck-input and wiring checks
- **AIM Ghost control labels:** buttons show the F-16 cockpit control they map to
- **Always-on-top** toggle and a remembered window size
- **Automatic update check** with an in-app banner

### Install

- Code-signed installer (Invictus Machine LLC), per-user, no administrator
  rights required.
