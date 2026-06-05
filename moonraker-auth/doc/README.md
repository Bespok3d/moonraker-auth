# Moonraker Login

Requires a login to access the printer's web interface and API by turning on Moonraker's
`force_logins`.

## What it does

- Sets `[authorization] force_logins: true` (or `false`) in Moonraker, so Fluidd/Mainsail
  prompt for a user before granting access.

## Configuration

- **Force logins** (toggle): on requires authentication for every client; off leaves the
  interface open on your LAN.

## Notes

- Restarts Moonraker on install or config change.
- You still manage users in Moonraker as usual; this plugin only flips the enforcement
  switch.
