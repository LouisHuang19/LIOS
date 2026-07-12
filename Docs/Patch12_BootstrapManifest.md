# Patch 12 — Bootstrap Manifest

Version: v1.0.1

## Goal

Allow a new AI session to load LIOS from one machine-readable manifest:

```text
https://raw.githubusercontent.com/LouisHuang19/LIOS/refs/heads/main/bootstrap.json
```

## Why bootstrap.json

`LIOS_Core.md` explains the system to humans.

`bootstrap.json` tells AI:

- which file is the entry point
- which files are mandatory
- which files are optional
- which version is current
- which data files may be needed
- what to do if remote access fails

## Recommended Startup

Paste:

```text
🚀 啟動 LIOS
https://raw.githubusercontent.com/LouisHuang19/LIOS/refs/heads/main/bootstrap.json
```

## Backward Compatibility

The direct Core URL remains valid:

```text
https://raw.githubusercontent.com/LouisHuang19/LIOS/refs/heads/main/Core/LIOS_Core.md
```
