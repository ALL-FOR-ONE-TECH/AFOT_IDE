AFOT-IDE is a lightweight, keyboard-driven terminal IDE combining a powerful file explorer, code editor, and integrated terminal with multi-tab support. Built for developers who value speed, efficiency, and a distraction-free coding environment.
🚀 Download Latest Release | 📖 Documentation | 🐛 Report Issues

Why AFOT-IDE?
Perfect for developers, system administrators, and power users who want:
✅ Lightning-fast performance - Terminal-native IDE with minimal resource usage
✅ Full keyboard control - Navigate, edit, and execute without touching the mouse
✅ Integrated terminal - Real PTY terminal with multi-tab support built right in
✅ Cross-platform - Works seamlessly on Linux, macOS, and Windows
✅ No dependencies - Single binary, ready to run
✅ Developer-friendly - Perfect for remote servers, SSH sessions, and local development

Table of Contents

Features
Installation

Debian/Ubuntu
Windows
From Source


Quick Start
Documentation
Keyboard Shortcuts
Configuration
Use Cases
Troubleshooting
Contributing
Releases
License


Features
🗂️ File Explorer

Fast directory navigation with keyboard shortcuts
Quick file opening and directory traversal
Visual file tree representation
Jump to parent directories instantly
Change working directory on the fly

✏️ Code Editor

Syntax-aware text editing
Auto-indentation for clean code
Line-by-line navigation (Home/End)
Page navigation (PageUp/PageDown)
Basic text selection and manipulation
UTF-8 support for international characters

💻 Integrated Terminal

Real PTY terminal - Not just command execution, full shell support
Multi-tab support - Multiple terminal sessions in one window
Tab management - Easy switching between terminal tabs
Clipboard integration - Paste text directly into terminal
Process control - Send interrupts (Ctrl+C) to running processes
Shell compatibility - Works with bash, zsh, PowerShell, cmd, and more

⚡ Performance

Minimal resource usage - Runs on low-end systems
Fast startup time - Launch in milliseconds
Efficient rendering - Smooth scrolling and editing
Small footprint - Single binary under 10MB


Installation
Debian/Ubuntu
Download and install the .deb package:
bash# Download the package
wget https://github.com/ALL-FOR-ONE-TECH/AFOT_IDE/releases/download/v1.0.0/afot-ide_1.0.0_amd64.deb

# Install
sudo dpkg -i afot-ide_1.0.0_amd64.deb

# Fix dependencies if needed
sudo apt -f install -y

# Run AFOT-IDE
AFOT-IDE
Windows

Download AFOT-IDE.msi 

powershell AFOT-IDE

# Follow build instructions in the repository

Quick Start
Basic Usage
Launch AFOT-IDE from your terminal:
bash# Open in current directory
AFOT-IDE

# Open specific folder
AFOT-IDE /path/to/project

# Show help
AFOT-IDE --help
First Steps

Browse files - Use arrow keys in the Explorer panel
Open a file - Press Enter on a file to edit it
Edit code - Type naturally with auto-indent support
Open terminal - Press Ctrl+T for a new terminal
Run commands - Execute any shell command in the terminal
Switch panels - Use keyboard shortcuts to navigate


Documentation
Panels Overview
Explorer Panel
Navigate your project structure with keyboard efficiency:

↑/↓ - Move through files and directories
Enter - Open file or enter directory
Backspace - Go to parent directory
Works with large directory trees efficiently

Editor Panel
Edit your code with essential features:

Full text editing with cursor control
Auto-indentation based on previous lines
Home/End - Jump to line start/end
PageUp/PageDown - Navigate pages
UTF-8 character support

Terminal Panel
A real terminal experience inside your IDE:

Full PTY terminal emulation
Multiple independent terminal tabs
Paste clipboard content with Ctrl+V
Interrupt processes with Ctrl+C
Supports all shell commands and interactive programs


Keyboard Shortcuts
Global Commands
ShortcutActionCtrl+QQuit AFOT-IDECtrl+POpen command paletteCtrl+SpaceToggle dashboard
Explorer
ShortcutAction↑/↓Navigate filesEnterOpen file/directoryBackspaceParent directory
Editor
ShortcutActionArrow KeysMove cursorHome/EndLine start/endPageUp/PageDownScroll pagesBackspaceDelete previous characterEnterNew line with auto-indent
Terminal
ShortcutActionCtrl+TNew terminal in current tabCtrl+Shift+TNew terminal tabCtrl+TabNext terminal tabCtrl+Shift+TabPrevious terminal tabCtrl+CInterrupt process (SIGINT)Ctrl+VPaste from clipboard

Note: Keybindings can be customized via configuration files.


Troubleshooting
IDE Won't Start

Ensure the binary is executable: chmod +x AFOT-IDE
Check if binary is in PATH or use absolute path
On Windows: Check antivirus/execution policy

Terminal Not Working

Verify default shell exists: which bash or where powershell
Try different shell in configuration
Check shell works independently

Display Issues

Ensure UTF-8 locale: export LANG=en_US.UTF-8
Use a modern terminal emulator
Try different terminal: iTerm2, Windows Terminal, GNOME Terminal

Performance Issues

Close unused terminal tabs
Reduce scrollback buffer size in config
Check system resources

Still having issues? Report a bug with:

Operating system and version
AFOT-IDE version
Steps to reproduce
Error messages


Contributing
We welcome contributions from the community! 🎉
How to Contribute

Fork the repository
Create a feature branch: git checkout -b feature/amazing-feature
Commit your changes: git commit -m 'Add amazing feature'
Push to the branch: git push origin feature/amazing-feature
Open a Pull Request

Reporting Issues
Found a bug? Have a feature request?

Search existing issues first
Create a new issue with:

Clear, descriptive title
Steps to reproduce
Expected vs actual behavior
System information
Error logs if applicable



Development
Check for project-specific guidelines:

Linting: Follow existing code style
Testing: Add tests for new features
Documentation: Update README and docs


Releases
Latest Version: v1.0.0
📥 Download v1.0.0
See RELEASES.md for detailed release notes, changelogs, and installation instructions for all versions.
Release History

v1.0.0 (2025-10-23) - Initial public release


License
Proprietary License - All rights reserved by ALL-FOR-ONE-TECH
This is proprietary software. For commercial use, redistribution, or licensing questions, please contact the maintainers.

Developer
Created and maintained by MR.V2K (karthikeyanV2K)
Developer at ALL-FOR-ONE-TECH
Signed by: MR.V2K
Developer, ALL-FOR-ONE-TECH

Links

🏠 Homepage: github.com/ALL-FOR-ONE-TECH/AFOT_IDE
📦 Releases: github.com/ALL-FOR-ONE-TECH/AFOT_IDE/releases
🐛 Issues: github.com/ALL-FOR-ONE-TECH/AFOT_IDE/issues
💬 Discussions: github.com/ALL-FOR-ONE-TECH/AFOT_IDE/discussions

