

<p align="center">
  <img src="assets/GluaToolsStudio.png" alt="GluaToolsStudio.png" width="750">
</p>

<p align="center">
  A modern Steam Lua, plugin, manifest, and developer utility.
</p>

# GLuaTools Studio Edition

**GLuaTools Studio Edition** is the power-user version of GLuaTools, built for developers, modders, plugin creators, and advanced Steam users who want a complete workspace for managing Lua files, Steam tools, plugins, debugging, profiles, and development workflows from one application.

Studio Edition expands the standard GLuaTools experience into a full development environment with a custom desktop interface, advanced plugin management, Steam DevTools integration, workspace profiles, diagnostics, theme customization, update tools, rollback support, and deeper configuration options.

The goal of Studio Edition is to bring the most important GLuaTools workflows together into a single organized workspace instead of requiring users to jump between folders, scripts, GitHub releases, Steam directories, debugging tools, and external utilities.

## Studio Workspace

Studio Edition introduces a dedicated **Studio Workspace** system.

Workspaces allow you to create different development environments and switch between them quickly.

A workspace can remember things such as:

* Active theme
* Marketplace source
* Advanced tool settings
* Development preferences
* Plugin workflow configuration
* Studio-specific settings

You can create multiple workspaces for different projects, duplicate existing setups, update a workspace with your current configuration, or switch between development environments with one click.

This makes it easy to maintain separate setups for testing, plugin development, content creation, debugging, or everyday Steam use.

## Advanced Plugin Center

GLuaTools Studio includes an expanded plugin management system designed to make installing and maintaining plugins much easier.

Features include:

* Plugin Marketplace
* GitHub-based plugin releases
* Search and filtering
* Plugin installation
* Plugin updates
* Update All
* Enable / disable plugins
* Installed plugin tracking
* Version comparison
* SHA-256 verification when available
* Automatic backups
* Plugin rollback
* Uninstall support
* Prerelease support
* Offline marketplace caching
* Millennium plugin support
* GLuaTools-managed plugin support

The Plugin Center is designed to work more like a package manager than a traditional manual plugin installer.

## Steam DevTools

Studio Edition includes a dedicated **Steam DevTools** environment for developers working with Steam’s frontend.

It can interact with Steam’s Chromium DevTools Protocol interface and provide information about available Steam browser targets.

Features include:

* Steam process detection
* CDP connection status
* Port 8080 diagnostics
* Steam target discovery
* Open Steam DevTools
* Reload Steam UI
* Restart Steam
* Open Steam installation folder
* Open Millennium folder
* Open plugin folders
* CDP target information
* Developer diagnostics

These tools make Studio Edition especially useful for Steam frontend development and plugin debugging.

## Lua Management

GLuaTools Studio keeps the original Lua management features while integrating them into the redesigned interface.

You can manage:

* Lua entries
* Imported Lua files
* Installed scripts
* Script locations
* Existing GLuaTools Lua workflows
* Steam-related Lua utilities

The Lua tools remain compatible with the existing GLuaTools backend while gaining access to the newer Studio interface and development features.

## Builds, Depots, and Steam Tools

Studio Edition also preserves the existing Steam workflow tools.

This includes support for:

* Builds
* Depots
* Downloads
* Steam paths
* Mode tools
* Fix Center
* Steam utility actions
* Installation helpers
* Existing GLuaTools Steam workflows

Studio is designed to expand GLuaTools rather than remove the functionality users already rely on.

## Themes

Studio Edition includes the complete GLuaTools theme system along with exclusive Studio themes.

Studio-exclusive themes include:

* **Studio Graphite**
* **Studio Gold**
* **Studio Aurora**

These are added alongside the standard GLuaTools themes.

Themes can change the appearance of:

* Sidebar
* Page backgrounds
* Cards
* Borders
* Accent colors
* Text colors
* Status elements
* Developer pages

The signature Studio identity uses a **black, silver, and blue** visual style.

## Diagnostics

Studio includes diagnostics tools intended for development and troubleshooting.

You can export a diagnostic snapshot containing information such as:

* GLuaTools Studio version
* Windows version
* Runtime version
* Current theme
* Marketplace configuration
* Plugin settings
* Advanced tools configuration
* Workspace information
* Relevant Studio settings

Diagnostic exports are saved as JSON so they can easily be shared when troubleshooting an issue.

## Expanded Settings

Studio Edition includes a larger Settings area for users who want more control over the application.

Settings can include options for:

* Theme selection
* Plugin auto updates
* Marketplace URL
* Plugin backups
* Prerelease plugins
* Advanced tools
* DevTools refresh interval
* Steam restart confirmation
* Startup behavior
* Minimize behavior
* Compact sidebar
* Update checks
* Developer settings
* Interface preferences

Studio Edition is intended to expose more configuration instead of hiding advanced options.

## Safety and Rollback

GLuaTools Studio tries to make plugin updates safer by using temporary staging locations and backups before replacing existing installations.

The typical update flow is:

1. Check for a new GitHub release
2. Download the release asset
3. Verify the file when a release digest is available
4. Extract to a temporary staging directory
5. Backup the current plugin
6. Replace the installed version
7. Update the local plugin registry
8. Keep the previous version available for rollback

If an update causes problems, users can restore the previous plugin version.

## Designed for Power Users

GLuaTools Studio Edition is aimed at users who want more than a basic installer.

It is especially useful for:

* Steam mod developers
* Lua developers
* Plugin creators
* Frontend modders
* Advanced GLuaTools users
* Debugging and testing
* Content creators with multiple mod setups
* Users maintaining several development configurations

## Edition Information

**Product:** GLuaTools Studio Edition
**Edition:** Studio
**Version:** 2.0
**Primary Style:** Black + Silver/Blue
**Focus:** Development, plugins, debugging, customization, and advanced Steam workflows

**GLuaTools Studio Edition — more tools, more control, one complete workspace.**

