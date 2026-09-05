# Custom Nano Editor Configuration (`nanorc`)

A clean, production-ready `nanorc` configuration optimized for systems administration, configuration management, and CLI editing without bloat.

## Features

- **Syntax Highlighting:** Includes definitions for system configuration files (`.conf`, `.ini`), shell scripts, YAML, JSON, Dockerfiles, and network configs.
- **Visual Polish:** Enables line numbers, smooth scrolling, and title bar formatting for headless server environments.
- **POSIX Alignment:** Tab-to-space conversions, strict 4-space indentation, and trailing whitespace auto-trimming.
- **Safety Hardening:** Auto-backups enabled before editing critical system files.

---

## Installation

### System-Wide Installation (Root / Admin)

Apply the configuration globally across all system users:

```bash
sudo cp nanorc /etc/nanorc
```
### User-Level Installation
​Apply the configuration exclusively for the current user:

``bash
cp nanorc ~/.nanorc
```