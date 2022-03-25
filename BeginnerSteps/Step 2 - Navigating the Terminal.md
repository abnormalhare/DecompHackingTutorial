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

Resources:
- List of all terminal commands: https://ss64.com/bash/
