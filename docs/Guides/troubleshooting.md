# Troubleshooting Guide

## Overview

This guide covers common issues encountered while using Visual Studio Code (VS Code) on Linux and their solutions.

## 1. VS Code Not Opening

Try launching VS Code from the terminal.

```bash
code
If it does not open, restart your system and try again.

2. Command Not Found
If the terminal displays code: command not found, verify that VS Code is installed.

bash
code --version
If necessary, reinstall VS Code using the appropriate installation method.

3. Extensions Not Working
Check your internet connection.

Open the Extensions panel.

Update or reinstall the affected extension.

Restart VS Code.

4. Terminal Not Working
Open a new terminal from Terminal → New Terminal. If the problem persists, check your default shell settings.

5. Permission Errors
Avoid running VS Code with sudo for normal development. Check the file permissions of your project directory.

bash
ls -l
6. VS Code Not Updating
For installations using Snap, run:

bash
sudo snap refresh code
For APT installations, run:

bash
sudo apt update
sudo apt upgrade code
Conclusion
Most VS Code issues can be resolved by checking the installation, updating extensions, and verifying system settings. If a problem persists, consult the official documentation.