 EN



# Guested_One Antivirus — 1.0.0

**G1 Security Platform · Первый стабильный публичный релиз**

Guested_One Antivirus is a Python desktop security utility built around local file scanning, heuristic checks, quarantine management, process inspection, local configuration, and optional plug-ins. The application is authored by **Первый_Гостевой (Guested_One)**.

> **Important:** G1 is an experimental, heuristic security utility. It is not a certified antivirus product, does not provide kernel-level or guaranteed real-time protection, and cannot guarantee detection of every threat. Keep your operating system security tools enabled and maintain backups.

## Features

- Tkinter desktop interface with a separate, windowed startup splash screen.
- File and directory scanning with fast, automatic, and deep modes.
- Heuristic detection for selected suspicious file patterns and the EICAR test signature.
- Quarantine manager, scan reports, activity log, and local Security Center.
- Process and network-endpoint inspection (extended details use optional `psutil`).
- Local plug-in catalog and a developer plug-in interface.
- Local assistant **ИИ_Гостевой** (rule-based knowledge assistant; not an LLM).
- Local-only profiles and leaderboard; no online leaderboard service is included.
- Backup and recovery for supported configuration data.
- Standalone Python Setup generator and uninstaller.
