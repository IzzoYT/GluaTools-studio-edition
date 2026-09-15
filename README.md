

<p align="center">
  <img src="assets/turnip.png" alt="GluaToolsStudio.png" width="750">
</p>

<p align="center">
  A modern steam app id center.
</p>

# TURNIP Loader

**TURNIP Loader** is a standalone Steam toolkit, plugin manager, theme studio, developer workspace, and diagnostics hub built for users who want one place to manage their Steam-related tools, customization, plugins, themes, local Lua content, integrations, and troubleshooting workflows.

TURNIP started as a heavily reworked version of the luatools codebase, but has since been expanded into its own standalone application with its own branding, application data paths, protocol handling, UI systems, utility pages, and development features.

The goal is simple: instead of having multiple separate tools scattered across folders, command-line utilities, plugin directories, config files, and browser tabs, TURNIP brings them together into one desktop application.

---

## What TURNIP is for

TURNIP is designed to act as a central control panel for:

* Steam-related development workflows
* local Lua project management
* plugin management
* Millennium management
* theme creation and customization
* Steam diagnostics
* application troubleshooting
* build and manifest inspection
* local workspace organization
* backups and restoration
* developer tools
* Steam process monitoring
* custom integrations
* game-specific quick actions
* local content management

TURNIP is intended to be modular so more systems can be added over time without turning the application into one giant hardcoded interface.

---

# Features

## Dashboard

The dashboard gives you a quick overview of your current TURNIP environment.

It can surface information such as:

* Steam installation status
* Steam process state
* active tools
* installed plugins
* Millennium detection
* TURNIP service status
* recent activity
* configured paths
* warnings and diagnostic issues

The dashboard is designed to become the main landing page for everything happening inside TURNIP.

---

## Steam Integration

TURNIP can detect your local Steam installation and provide common Steam-related actions directly from the application.

Current and planned tools include:

* detect Steam installation
* detect whether Steam is running
* open Steam installation folder
* restart Steam
* inspect Steam processes
* open relevant configuration folders
* display Steam-related status
* surface troubleshooting information
* integrate game-specific quick actions

TURNIP is not intended to replace Steam. It acts as a companion utility and management layer around your local Steam environment.

---

# Millennium Manager

TURNIP includes a dedicated **Millennium Manager**.

The Millennium Manager is intended to make working with a local Millennium installation easier without constantly navigating directories manually.

### Current functionality

* detect Millennium installation
* show detected Millennium version
* show Millennium root directory
* show plugin directory
* show theme directory
* display installed plugins
* refresh detected data
* open Millennium folders directly
* enable or disable supported plugin folders
* show basic Millennium health information

### Planned Millennium features

* plugin update checks
* dependency inspection
* incompatible plugin warnings
* theme management
* plugin search
* plugin information panels
* changelog display
* plugin error detection
* plugin backup and restore
* Millennium log viewer
* compatibility status with the current Steam client
* one-click configuration access

TURNIP is intended to act as a desktop management frontend for Millennium rather than modifying Millennium's core architecture.

---

# Theme Studio

TURNIP includes a built-in **Theme Studio** for visually customizing the application.

Instead of manually editing theme files, Theme Studio provides interactive controls.

### Theme controls

* accent color
* application background
* sidebar color
* corner radius
* transparency
* blur appearance
* font selection
* sidebar layout style

Example:

```text
THEME STUDIO

Accent Color      [██████]
Background        [██████]
Sidebar           [██████]

Corner Radius     ─────●──
Transparency      ──●─────
Blur              ─────●──

Font              Segoe UI Variable ▼
Sidebar Style     Comfortable ▼

[ Live Preview ] [ Apply ] [ Export Theme ]
```

### Live Preview

Live Preview allows you to experiment with the interface without permanently saving the theme.

This is useful when adjusting:

* colors
* spacing
* font choice
* corner radius
* sidebar size
* transparency

### Apply Theme

The Apply action saves your custom theme and makes it the active TURNIP theme.

Custom themes are stored in the TURNIP application data directory.

Example:

```text
%AppData%\TURNIPStudio\themes\
```

### Theme Export

Custom themes can be exported into portable theme packages so they can be:

* backed up
* shared
* moved between computers
* imported into future TURNIP versions

Future versions are planned to include a full theme browser and community theme ecosystem.

---

# Plugin Center

TURNIP includes a plugin management system intended to allow the application to grow without requiring every feature to be part of the core executable.

The Plugin Center can support:

* installed plugin listing
* local ZIP installation
* plugin enable / disable
* plugin metadata
* compatibility information
* dependencies
* version information
* update availability
* plugin diagnostics

The long-term goal is for plugins to be able to add:

* sidebar pages
* buttons
* commands
* developer utilities
* integrations
* game tools
* status widgets

This allows TURNIP to remain extensible while keeping the core application manageable.

---

# Lua Library

TURNIP includes a workspace for managing local Lua content.

The Lua Library is designed for developers and modders who work with many scripts and project folders.

Features include:

* scan configured folders for `.lua` files
* browse local Lua scripts
* inspect paths
* view modification times
* organize workspace files
* open script locations
* integrate local Lua projects into TURNIP workflows

Future improvements may include:

* tags
* favorites
* syntax preview
* search
* project grouping
* diff viewer
* version history
* editor integration

---

# Builds & Depots

TURNIP includes tools for inspecting local build-related information and supported manifest files.

Possible supported local file types include:

* `.acf`
* `.vdf`
* `.manifest`
* locally configured build information

The goal is to provide a visual interface for understanding locally available Steam-related build data.

TURNIP does not need to make users manually dig through Steam directories just to locate basic metadata.

---

# Fix Center

The **Fix Center** is TURNIP's centralized troubleshooting area.

Instead of forcing users to search through configuration folders manually, Fix Center can identify common problems and offer safe corrective actions.

Examples include:

* missing folders
* invalid configured paths
* stale configuration
* duplicate files
* plugin conflicts
* missing dependencies
* disconnected services
* malformed settings
* unavailable Steam paths
* broken local integrations

Future versions can expand this into a more complete health-check system.

---

# Power Tools

TURNIP's Power Tools page provides maintenance and utility functions.

Current features include:

### Backup

Create backups of important TURNIP data such as:

* settings
* themes
* local workspace information
* supported application state

Temporary files and caches can be excluded to keep backups clean.

### Restore

Restore a previously created TURNIP backup package.

Restore operations include path validation to reduce the chance of unsafe or malformed archives writing files outside the intended application area.

### Diagnostics Export

TURNIP can generate a diagnostic report containing useful troubleshooting information such as:

* operating system version
* .NET version
* Steam path
* Steam status
* TURNIP data path
* Lua file count
* plugin folder status
* configured integration status

Sensitive credentials and authentication information should not be included in exported diagnostic files.

### Quick Locations

Open frequently used directories directly:

* TURNIP data folder
* Steam folder
* Lua folder
* plugin folder
* Windows temporary directory
* downloads directory

---

# Developer Tools

TURNIP contains a developer-focused toolset intended for debugging local integrations and application behavior.

The long-term Developer Tools area is planned to provide:

* Steam connection information
* frontend bridge state
* plugin host state
* local HTTP service state
* process information
* active AppID
* recent plugin errors
* local logs
* service restart controls
* diagnostics copying
* plugin reload controls
* theme reload controls

The aim is to make TURNIP useful not only for end users, but also for people creating tools and integrations around it.

---

# Platform Insights

Platform Insights provides a higher-level overview of the current environment.

This area can be used for:

* compatibility information
* service health
* detected integrations
* bridge monitoring
* activity tracking
* warning detection

A future health score system may summarize the environment in a simple format:

```text
TURNIP HEALTH

Steam detected             ✓
TURNIP services running    ✓
Millennium detected        ✓
Plugin bridge healthy      ✓
Theme system healthy       ✓

Warnings:
2 outdated plugins
1 configuration issue
```

---

# Command Palette

TURNIP includes a command palette accessible with:

```text
Ctrl + K
```

This provides a fast way to navigate and run common actions without searching through the sidebar.

Example commands:

```text
Dashboard
Add Content
Lua Library
Builds & Depots
Mode & Tools
Fix Center
Plugin Center
Millennium Manager
Power Tools
Developer Tools
Platform Insights
Theme Studio
Settings
Restart Steam
Open Steam Folder
Open TURNIP Data
```

The command palette supports:

* text filtering
* keyboard navigation
* Enter to execute
* Escape to close

The command palette is planned to eventually index games, plugins, settings, files, and external integrations too.

---

# TURNIP Protocol

TURNIP supports its own application protocol:

```text
turnip://
```

Example routes may include:

```text
turnip://home
turnip://plugins
turnip://game/<appid>
turnip://manage/<appid>
turnip://fix/<appid>
```

Legacy protocol support may remain available in some builds for compatibility with older integrations.

---

# Standalone Application Data

TURNIP uses its own application data location:

```text
%AppData%\TURNIPStudio
```

This separates TURNIP's standalone state from the older GLuaTools application data directory.

This directory may contain:

```text
settings.json
themes\
plugins\
marketplace\
cache\
logs\
backups\
workspace\
```

Exact contents may change between versions as systems are reorganized.

---

# Custom Branding

TURNIP uses its own application identity.

Current branding includes:

* TURNIP Loader logo
* custom purple TURNIP icon
* TURNIP Studio product name
* TURNIP-specific application data
* TURNIP protocol
* TURNIP-specific startup and utility scripts

The interface uses a dark desktop-style design with purple accents by default.

---

# Project Structure

A simplified project structure looks similar to:

```text
TURNIP
│
├── src
│   └── GLuaToolsGui
│       ├── Models
│       ├── Services
│       ├── ViewModels
│       ├── Views
│       ├── Resources
│       ├── App.xaml
│       ├── MainWindow.xaml
│       └── icon.ico
│
├── tests
├── built-in-plugins
├── scripts
├── OPEN-ME-TURNIP-STUDIO.sln
├── RUN-TURNIP.cmd
└── README.md
```

Some internal namespaces may still retain historical names while the application continues transitioning into the standalone TURNIP architecture.

Those names are implementation details and are being progressively separated from the product-facing TURNIP identity.

---

# Requirements

TURNIP currently targets Windows.

Typical development requirements:

```text
Windows 10 / 11
.NET 8
Visual Studio 2022+
Desktop development with .NET workload
```

The project uses WPF for its desktop interface.

---

# WPF Build Cache Issues

If Visual Studio reports errors involving generated files such as:

```text
DownloadsView.g.i.cs
GeneratedInternalTypeHelper.g.i.cs
```

and says the files are in use by another process, close Visual Studio and terminate any remaining:

```text
MSBuild.exe
dotnet.exe
devenv.exe
```

processes before rebuilding.

Some TURNIP builds include:

```text
RESET-TURNIP-BUILD-CACHE.cmd
BUILD-TURNIP-SAFE.cmd
```

to simplify clearing generated build state.

---

# Safety and Scope

TURNIP is intended as a desktop management, customization, development, and diagnostics application.

Its focus is on:

* local tooling
* mod development
* legitimate plugin ecosystems
* configuration management
* diagnostics
* workspace organization
* Steam client customization
* user-provided local files

TURNIP is not intended to be a piracy utility or a replacement for legitimate software ownership.

Users are responsible for following the terms, licenses, and rules of the software and services they use with TURNIP.

---

# Planned Features

There is still a lot planned for TURNIP.

### Game Workspaces

Dedicated dashboard for each installed game:

```text
GAME WORKSPACE

Garry's Mod
AppID 4000

Launch
SteamDB
Install Folder
Workshop
Config
Screenshots

Launch Options
Lua Files
Mods
Workshop Content
Logs
Backups
Tools
```

---

### TURNIP Hub

A centralized extension browser for:

* plugins
* themes
* integrations
* developer extensions

Planned Hub features:

* install
* update
* uninstall
* dependency management
* compatibility status
* changelogs
* screenshots
* categories
* search
* favorites

---

### Health Center

A full system health and conflict scanner.

Planned checks:

* plugin conflicts
* duplicate installations
* broken theme files
* missing dependencies
* invalid paths
* Steam service state
* stale cache
* broken configurations
* integration conflicts

---

### Notification Center

Central history for TURNIP events:

```text
Plugin installed
Plugin updated
Steam restarted
Theme applied
Backup completed
Millennium detected
Configuration warning
```

---

### Profiles

Different TURNIP layouts and configurations for different workflows:

```text
Gaming
Modding
Developer
Minimal
Custom
```

---

### Portable Mode

Run TURNIP without writing configuration into AppData.

Portable mode would keep data beside the executable:

```text
TURNIP\
  TURNIPStudio.exe
  Data\
  Themes\
  Plugins\
  Settings\
```

---

### Safe Mode

Launch TURNIP with optional systems temporarily disabled:

```text
TURNIP SAFE MODE

[x] Disable third-party plugins
[x] Disable custom themes
[ ] Disable Steam integration
[ ] Reset window layout

Launch
```

Useful when a plugin or theme prevents normal startup.

---

### Activity Timeline

A chronological view of TURNIP activity:

```text
15:42 Steam started
15:42 TURNIP bridge connected
15:43 Millennium detected
15:44 Theme loaded
15:46 Plugin updated
15:48 Backup completed
```

---

# Design Philosophy

TURNIP is being built around a few basic ideas.

### One place for everything

Common Steam development and customization tools should not require jumping through ten different folders and applications.

### Local-first

TURNIP should still be useful when offline.

Local configuration, projects, plugins, themes, logs, and diagnostics remain central to the application.

### Extensible

TURNIP should not need a complete application update every time somebody wants to add a new tool.

Plugins and integrations should be able to extend it.

### Transparent

TURNIP should clearly show what it detects and what action it is about to perform.

### Recoverable

Features that alter configuration should prefer backups, safe writes, validation, and recovery paths.

### Developer-friendly

Logs, diagnostics, paths, services, and status information should be easy to access.

---

# Current Status

TURNIP is currently an **alpha-stage project**.

Expect:

* unfinished pages
* changing APIs
* UI changes
* incomplete integrations
* occasional bugs
* breaking changes between alpha versions

If you are testing TURNIP, reporting exact errors and reproduction steps is extremely helpful.

---

# Contributing

Contributions are welcome as TURNIP becomes more standalone and modular.

Useful contribution areas include:

* WPF UI improvements
* accessibility
* themes
* diagnostics
* plugins
* localization
* Millennium integration
* game workspace tools
* Steam metadata parsing
* documentation
* testing
* crash reporting
* performance improvements

For larger changes, opening an issue or discussion before implementing a major subsystem is recommended.

---

# Bug Reports

When reporting a bug, include:

```text
TURNIP version:
Windows version:
.NET version:
Steam version:
Millennium installed:
Steps to reproduce:
Expected result:
Actual result:
Error message:
```

If possible, also attach a TURNIP diagnostic export.

Do not upload passwords, authentication tokens, API credentials, or private account information.

---

# License

See the repository's `LICENSE` file for the current project license.

---

# TURNIP Loader

**One app. Your tools. Your workflow.**

```text
BUILD
MOD
DEBUG
CUSTOMIZE
MANAGE
```

**TURNIP Loader** is still early, but the goal is to turn it into a complete desktop toolkit for Steam developers, modders, plugin creators, and power users.


