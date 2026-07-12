# Remote Bootstrap

Version: v1.0.1

## Preferred Entry Point

Use:

https://raw.githubusercontent.com/LouisHuang19/LIOS/refs/heads/main/bootstrap.json

The bootstrap file declares:

- current LIOS version
- required documents
- recommended documents
- optional documents
- boot sequence
- fallback behavior

## Legacy Entry Point

The following direct Core URL remains supported:

https://raw.githubusercontent.com/LouisHuang19/LIOS/refs/heads/main/Core/LIOS_Core.md

## Boot Workflow

1. Read `bootstrap.json`.
2. Read all `required_documents` in order.
3. Load `recommended_documents` only when relevant.
4. Ask for Portfolio / Replay / Journal data only when needed.
5. Treat GitHub repository files as the source of truth.

## Fallback

If the remote files cannot be accessed:

1. Ask the user to upload `bootstrap.json`.
2. Ask the user to upload `Core/LIOS_Core.md`.
3. Do not reconstruct LIOS rules from memory.
