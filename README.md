# JARVIS Display Manager update channel

This public repository is the verified update channel for Patrick's JARVIS ESP32 display manager.

The manager checks `update.json`, downloads the encoded release package over HTTPS, verifies its SHA-256 checksum, and installs it through the local-only updater service. Printer credentials, display tokens, uploaded themes, printer selection, and settings are not stored here and are preserved during updates.

The display manager is visual-only and does not expose printer-control actions.
