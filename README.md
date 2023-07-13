# Windows 11 Context Menu Tweaks

This repository contains two programs for customizing the Windows 11 context menu.

## DisableWin11ContextMenu.bat

This program disables the 'Show More Options' item in the Windows 11 context menu. To use it, simply double-click on the `DisableWin11ContextMenu.bat` file. This will add a registry key and restart the `explorer.exe` process, effectively disabling the 'Show More Options' item in the context menu.

## EnableWin11ContextMenu.bat

This program enables the 'Show More Options' item in the Windows 11 context menu. To use it, double-click on the `EnableWin11ContextMenu.bat` file. This will delete the registry key added by the `DisableWin11ContextMenu.bat` program and restart the `explorer.exe` process, effectively enabling the 'Show More Options' item in the context menu.

## Usage

To use these programs, simply download the `.bat` files from this repository and double-click on them to run. You can also run them from the command line by navigating to the directory where they are saved and running `DisableWin11ContextMenu.bat` or `EnableWin11ContextMenu.bat`.

## Disclaimer

These programs modify the Windows registry and restart the `explorer.exe` process. While they have been tested and should be safe to use, please use them at your own risk. It is always a good idea to backup your system before making any changes.
