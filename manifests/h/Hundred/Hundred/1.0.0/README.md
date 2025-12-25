# Hundred Package Manifest

## Overview
This directory contains the package manifest for "Hundred" application version 1.0.0.

## Purpose
This manifest was created in response to the issue "Hundred" which did not provide additional context. The manifest serves as:
- A template demonstrating proper winget package structure
- An example following winget-pkgs repository conventions
- A placeholder that can be updated with actual application details

## Files
- `Hundred.Hundred.yaml` - Version manifest
- `Hundred.Hundred.installer.yaml` - Installer configuration
- `Hundred.Hundred.locale.en-US.yaml` - English locale information

## Important Note
⚠️ **This is an example manifest with placeholder values**:
- URLs use `example.com` placeholder domain
- SHA256 hash is a placeholder (all zeros)
- Installer URL is not functional

To make this manifest production-ready:
1. Replace all example.com URLs with actual application URLs
2. Update the InstallerSha256 with the real hash of the installer
3. Provide actual InstallerUrl pointing to the real installer download
4. Update publisher, copyright, and description with real information

## Usage
This manifest follows the standard winget package format and can be validated using:
```powershell
winget validate manifests/h/Hundred/Hundred/1.0.0
```

## Structure
The manifest follows the multi-file manifest format (v1.4.0) as documented in the winget-pkgs repository.
