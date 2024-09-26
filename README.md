# PowerShell Profile Enhancement

## Overview

This repository contains a set of PowerShell scripts and configurations designed to enhance the PowerShell experience on Windows systems. The main components include a customized PowerShell profile, a setup script, and supporting files for improved functionality and aesthetics.

## Contents

1. `.gitignore`: Specifies intentionally untracked files to ignore.
2. `Microsoft.PowerShell_profile.ps1`: The main PowerShell profile script.
3. `README.md`: Provides installation instructions and an overview of the project.
4. `setup.ps1`: An installation script to set up the enhanced PowerShell environment.
5. `.github/FUNDING.yml`: GitHub funding configuration file.

## Key Features

### PowerShell Profile (`Microsoft.PowerShell_profile.ps1`)

- **Module Imports**: Automatically imports necessary modules like Terminal-Icons.
- **Auto-Update**: Checks for profile updates from the GitHub repository.
- **PowerShell Update Check**: Ability to check and update PowerShell itself.
- **Admin Check**: Modifies the prompt to indicate when running as administrator.
- **Utility Functions**: Includes various helper functions for common tasks.
- **Aliases**: Defines useful aliases for frequent operations.
- **Git Shortcuts**: Provides quick commands for Git operations.
- **Environment Management**: Functions to set, remove, and get system environment variables.
- **Cache Clearing**: Function to clear system-level cache.
- **Oh My Posh Integration**: Configures Oh My Posh for a customized prompt.
- **Zoxide Integration**: Sets up Zoxide for improved directory navigation.

### Setup Script (`setup.ps1`)

- **Elevated Privileges Check**: Ensures the script runs with proper permissions.
- **Internet Connectivity Check**: Verifies internet connection before proceeding.
- **Profile Installation**: Downloads and installs the custom PowerShell profile.
- **Oh My Posh Installation**: Installs Oh My Posh for prompt customization.
- **Font Installation**: Downloads and installs the CaskaydiaCove NF font.
- **Chocolatey Installation**: Sets up the Chocolatey package manager.
- **Terminal Icons Installation**: Installs the Terminal-Icons module.
- **Zoxide Installation**: Installs Zoxide for enhanced directory navigation.

## Usage

1. Run the setup script in an elevated PowerShell session:
   ```powershell
   irm "https://github.com/ChrisTitusTech/powershell-profile/raw/main/setup.ps1" | iex
   ```
2. Follow any on-screen instructions, particularly for font installation.
3. Restart PowerShell to apply the changes.

## Inputs

- User confirmation for various installation steps.
- Internet connection for downloading necessary components.

## Outputs

- Enhanced PowerShell environment with custom profile.
- Installed tools: Oh My Posh, CaskaydiaCove NF font, Chocolatey, Terminal-Icons, Zoxide.
- Modified system settings (e.g., fonts, environment variables).

## Notes

- Ensure you have administrator privileges before running the setup script.
- Backup any existing PowerShell profiles before installation.
- Some features may require additional configuration or system restarts to take full effect.