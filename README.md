# winHelp | Windows Setup Automation

**Set up your Windows development environment without the repetitive manual work.**

winHelp is a PowerShell-based utility with a native WPF interface designed to simplify Windows provisioning. It brings application installation, developer-tool configuration, system customization, and configuration backups together in one place.

Instead of configuring every tool individually on a fresh installation, users can manage supported setup tasks through a centralized GUI backed by editable JSON configuration files.

## Why winHelp?

Setting up a new Windows machine often means repeating the same steps: installing applications, configuring Git, restoring editor settings, and adjusting system preferences.

winHelp aims to make that process more organized, repeatable, and easier to customize.

## Core Capabilities

### 01 — Application Management
- Browse applications by category.
- Select packages for installation or removal.
- Use WinGet to manage supported applications.

### 02 — Developer Environment
- Configure global Git settings.
- Use GitHub CLI for authentication and repository workflows.
- Set up supported editors and IDEs.
- Deploy extensions, editor settings, and Neovim configuration.

### 03 — Windows Customization
- Apply supported privacy-related tweaks.
- Remove selected preinstalled AppX packages.
- Manage supported search-related settings.

### 04 — Configuration Recovery
- Back up selected registry keys and files.
- Restore supported configurations.
- Maintain
