# suspend-then-shutdown

Tiny systemd sleep hook that wakes after a set delay and powers off automatically, so suspend won't drain your battery—no hibernation required.

**Install (from repo root:**
```
sudo install -m 755 -o root -g root suspend-then-shutdown /usr/lib/systemd/system-sleep/suspend-then-shutdown
```
