# suspend-then-shutdown

Tiny systemd sleep hook that wakes after a set delay and powers off automatically, so suspend won't drain your battery—no hibernation required.

**Install from repo root:**
```
sudo mkdir -p /usr/lib/systemd/system-sleep/
sudo install -m 755 -o root -g root suspend-then-shutdown /usr/lib/systemd/system-sleep/suspend-then-shutdown
```

Must use systemd, install path differs between distros.
Debian/Ubuntu/Mint: /lib/systemd/system-sleep/
Fedora/Arch/openSUSE: /usr/lib/systemd/system-sleep/

Default timer is 4 hours, adjust as needed.
