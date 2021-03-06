## Step 2: WSL and Navigating the Ubuntu Terminal

The terminal used for HackerSM64 is a bit different from your average Windows Terminal, and you may not know how to use a terminal at all! Here are some commands you'll need to use on your journey forward:

- Dictionary
  - Directory: Location of what folder you are in
  - Root: `/`, essentially `C:\` for your terminal
  - Home: `/home/<user>`: essentially `C:\Users\<user>` for your terminal
  - Build: to turn a set of files and folders into an executable file.

- `cd <folder>`: Moves you to a selected folder.
  - `cd ..`: Moves up a folder (eg `/this/folder/` -> `/this/`) [Note: you are not able to use `cd..`]
  - `cd /[path]`: Moves you to the root directory, or to a folder starting at the root directory
  - `cd ~[/path]`: Moves you to the home directory, or to a folder starting at the home directory
- `ls`: Shows all non-hidden folders and files in the directory you're in.
  - `ls -a`: Shows all folders and files in the directory you're in.
- `mnt/c`: Your literal "c drive" for Ubuntu, though not recommended to use for HackerSM64, as it can cause slower building times and even corrupt your data when building.
- `sudo <command>`: Runs a command in "Superuser" mode, allowing you to do more things than normal. This isn't always necessary.
- `make`: A command from `gcc` that builds C/C++ apps.

In order for Blender to be able to see WSL, you have to connect it to a network drive:
1. Open File Explorer -> Linux
2. Right-Click on `Ubuntu`, `Show more options` (Windows 11), `Map network drive...`, then click `Finish` on the prompt.
3. In Blender, click the arrow on the right by the outliner -> `SM64` -> `SM64 File Settings` -> `Deco...`  
4. Click on the folder icon and type `\\wsl.localhost\Ubuntu\home\` into the bar at the bottom.

Resources:
- List of all terminal commands: https://ss64.com/bash/
