# Attributions - moonraker-auth

**Plugin author:** Bespok3d, switching on a Moonraker option that the Extended Firmware overlay `32-feature-klipper-tweaks` (paxx12) also switches on

Turns on Moonraker's built-in authentication.

This package ships two lines of Moonraker configuration: the `[authorization]` section and the
`force_logins` option, both Moonraker's own names. The Extended Firmware overlay
`32-feature-klipper-tweaks` (paxx12), GPL-3.0, sets the same option, so those two lines read the
same in both. The authentication itself is Moonraker's.

## Why this package is licensed as Bespok3d's own work

Two configuration lines are shared with that overlay, and both are Moonraker's own option names:
`[authorization]` and `force_logins`. Anyone switching this feature on writes the same two lines,
because they are the only names Moonraker accepts. That is too little to carry authorship, so no
part of the overlay's licence attaches to this package, and this repo is AGPL-3.0-or-later like the
rest of Bespok3d's own code.
