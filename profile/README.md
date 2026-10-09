# Sparewall

Sparewall is an open-source, image-based Linux firewall: a single node or an
HA pair, configured from one versioned document, built from systemd,
nftables and a small Rust coordinator.

- **Image-based and rollback-safe:** the OS is a signed bootc image; upgrades
  and rollbacks are reboots.
- **One source of truth:** one JSON/YAML document describes the deployment;
  every change is validated, applied atomically, and reverted unless confirmed.
- **HA when wanted:** the same image runs standalone or as an active/standby
  pair (keepalived, conntrackd, Kea HA) over a WireGuard sync tunnel.

The code lives in [sparewall/sparewall](https://github.com/sparewall/sparewall).
Sparewall is pre-release software and not yet ready for production use.
