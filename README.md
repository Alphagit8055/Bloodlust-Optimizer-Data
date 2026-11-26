# Bloodlust Optimizer public data

This repository contains only the online tweak catalog, license revocation policy, and public installer/update releases. The application's source repository is private. Never upload source code, license keys, or the signing private key here.

- `tweaks.json` is downloaded by the app on startup and synchronized by the private source repository's release workflow.
- `license-policy.json` lists SHA-256 license IDs to revoke.
- GitHub Releases contain the public Velopack installer and update feed.

The app requires the files in this repository to be reachable over HTTPS. License expiration uses the HTTPS response date and is rechecked while the app is running.
