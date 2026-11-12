# ⚙️ Homecoming Recovery Tool

### Restore the machine. Return to the world.

**Homecoming Recovery Tool (HRT)** is an open-source Linux utility designed to diagnose, verify, and repair installations of **City of Heroes: Homecoming**.

Its goal is simple: make recovering a broken or incomplete Homecoming installation on Linux easier, safer, and more accessible.

> *Even a damaged machine can be restored.*

---

## Overview

Running City of Heroes: Homecoming on Linux can involve several layers of compatibility and configuration: game files, the launcher, Wine prefixes, and third-party tools such as PortProton.

When something breaks, identifying the cause and repairing the installation can become unnecessarily complicated.

HRT aims to bring these tasks together in one modular recovery tool.

## Planned Features

- [ ] Detect existing Homecoming installations.
- [ ] Locate launchers and Wine prefixes.
- [ ] Detect PortProton environments.
- [ ] Verify game files using official manifests and checksums.
- [ ] Identify missing or corrupted files.
- [ ] Download required files from official sources.
- [ ] Diagnose common Wine and launcher issues.
- [ ] Back up and restore configuration files.
- [ ] Provide detailed diagnostic reports.

**Development status:** Early development. Features will be marked as supported only after implementation and testing.

## Compatibility

| Environment | Status |
|---|---|
| Arch Linux | Target platform |
| PortProton | Target environment |
| Wine | Planned |
| Lutris | Planned |
| Bottles | Planned |
| Other Linux distributions | Planned |

Compatibility claims will be updated as testing progresses.

## Installation

Clone the repository:

```bash
git clone https://github.com/Dalbonst/Homecoming_Recovery_Tool_Linux.git
cd Homecoming_Recovery_Tool_Linux
```

> Installation and launch instructions will be added when the initial runnable version is ready.

## Safety Principles

HRT is designed around several principles:

- No unnecessary root privileges.
- No silent deletion of user data.
- Backups before configuration changes.
- Explicit confirmation before potentially destructive operations.
- File integrity verification.
- Transparent logs and diagnostic reports.
- No fabricated manifests, checksums, or download sources.

## Documentation

- [Project Wiki](https://github.com/Dalbonst/Homecoming_Recovery_Tool_Linux/wiki)
- [Report a Bug](https://github.com/Dalbonst/Homecoming_Recovery_Tool_Linux/issues)
- [Contributing](CONTRIBUTING.md)

## Contributing

Contributions, bug reports, testing, and suggestions are welcome.

Before submitting changes, please read the contribution guidelines.

## Disclaimer

HRT is an independent community project. It is not affiliated with or endorsed by the City of Heroes: Homecoming team.

All game files remain the property of their respective owners. HRT is intended to work with legitimate installations and official distribution sources.

---

<p align="center">

**⚙️ RESTORE THE MACHINE. RETURN TO THE WORLD.**

*The machine does not forgive. The machine can be repaired.*

</p>
