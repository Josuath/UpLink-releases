# UpLink privacy policy

Effective date: 2026-11-25

UpLink is a remote-control app for your own Windows PCs, published by Majimi.

**What we collect.** Nothing. UpLink has no account, no ads, no analytics and no telemetry. The developer receives no
data from the app.

**Who it talks to.** UpLink connects only to the PCs you paired, directly over your local network or Tailscale. While you add a PC, it also looks for PCs on your local network (a broadcast on the local network that only UpLink PCs answer) and connects to the PC you pick to pair it. The
connection is encrypted (TLS), and the app checks the PC's certificate fingerprint. The screen, your keyboard and mouse
input and the optional shared clipboard travel only between your own devices.

**What it stores.** The pairing keys are stored on the PC, encrypted by Windows (DPAPI) for the current Windows user.
Logs stay on the PC and never contain keys or clipboard text.

**Updates.** The UpLink service's "Check for update" contacts GitHub's public API (api.github.com), and it downloads a
release from GitHub only when you click.

**Contact.** Questions about this policy: https://github.com/Josuath/UpLink-releases/issues
