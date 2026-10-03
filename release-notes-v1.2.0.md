# AIM Joystick Probe v1.2.0

The biggest update yet: the Probe now measures what matters when you build or
troubleshoot cockpit hardware, not just which buttons are pressed.

## What's new

### Axis quality
- **Travel and full range:** each axis shows how far it has gone each way,
  and ticks off with a ✓ once it reaches both ends.
- **Noise:** how much each axis jitters, as a share of its travel, in amber
  from 1% and red from 3%. Moving the axis doesn't count as noise.
- **Resolution:** each axis's effective resolution in bits, worked out from
  the smallest step it actually reports.
- **History:** a graph of the last 5 seconds, for one axis or all of them.
- **Real axis names:** axes show the names the device itself reports (Dial,
  Slider, Throttle or a maker's own). On AIM Ghost Joysticks, axis 7 is the
  Dial and axis 8 the Slider.

### Stick tools
- **X / Y trail:** the stick's path over the last 2 seconds, so you can see
  its gate shape, flat spots and full throw.
- **Centering:** a new card that marks where the stick comes to rest each
  time you let go, magnified 10x, with spread (how consistently it centers)
  and offset.

### Buttons and switches
- **Event log:** every press, release and hat move, timed to the millisecond,
  across all devices, with Copy and Clear.
- **Switch bounce:** a button that chatters on and off within a few
  milliseconds is flagged in the log and outlined in amber.
- **Test all** now covers axes too:
  "14 / 20 buttons · 2 / 2 axes full range".

### Devices
- **Report rate:** how often the selected device sends updates, in Hz.
- **Identical devices** are numbered ("Button Box (1)", "(2)") so they're
  never mixed up.
- **Force feedback (experimental):** spring, push and vibration effects for
  force feedback sticks, and a rumble test for gamepads.

### Sharing and support
- **Save snapshot:** saves the window as a picture, in a folder you choose.
- **Copy diagnostics:** a report of your devices for support requests,
  including any game controller Windows sees that the Probe doesn't.

### Your layout
- **Settings** (the gear at the top right): always on top, the X / Y trail,
  the snapshot folder, and a switch for every card.
- **Collapse any card** to its header by clicking its title.
- **Info icons** on every card open its section of the user guide.

## Fixes and polish
- Axis noise ignores devices that roll over from one end to the other (like
  3D mice), and high-resolution devices now measure correctly.
- The X / Y dot shows the true reading, without smoothing.
- The app now uses its own bundled fonts, so numbers line up in columns.
- No more "-0.00" in readouts.

## Install

Download **AIM-Joystick-Probe-v1.2.0-Setup.exe** below and run it. It installs
over your existing copy and keeps your settings. The installer now shows the
license agreement; the app is free to use and to share, unmodified. The
installer and the app are code-signed by Invictus Machine LLC, and it installs
per-user with no administrator rights needed.

## Documentation

The full user guide is at
[docs.invictuscockpits.com](https://docs.invictuscockpits.com/joystick-probe/user-guide/).
