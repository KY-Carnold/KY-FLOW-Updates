# KY-FLOW Updates

This repository contains the version manifest for KY-FLOW application updates.

## Purpose

This public repository serves as the source of truth for the latest KY-FLOW version. The installer and auto-updater check this manifest to determine:
- Current available version
- Package filename
- Update availability

## Files

- `ky-flow-version.json` - Version manifest containing current version information

## Usage

The manifest is accessed directly via:
```
https://raw.githubusercontent.com/KY-Carnold/KY-FLOW-Updates/main/ky-flow-version.json
```

## Security

This repository only contains version metadata - no source code or packages. The actual application packages are distributed through OneDrive within the organization.

## Updating

When deploying a new version:
1. Update `ky-flow-version.json` with the new version number and package filename
2. Commit and push to the `main` branch
3. The update becomes immediately available to all clients
