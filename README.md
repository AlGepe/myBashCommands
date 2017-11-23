# Custom Bash Commands

Collection of bash commands created by me to achieve extra functionality or simplify tasks

## Usage:

Add: `export PATH=$PATH":path/to/folder"` to [.bashrc] file and change permissions on executable files [chmod +x fileName]

For spotify shortcut wmctrl is needed `sudo apt install wmctrl` and spoti script must be placed in `/usr/bin/`

## newRepo $1 $2

Creates a new github repository with name $1 for user $2. $2 is optional and deafults to AlGepe (me).

## spoti

Checks if Spotify is opened to then open it (if not open) or bring window to front (if already open)

## gitUpdate

Updates git repositories for parent and child folders up decided by user[default= ./] up to depth input by user (default = 2)
 		Usage: `gitUpdate [folder] [depth]` or `gitUpdate -f/--folder [folder] -d/--depth [depth]`

## beforeIgo

Shows status for git repositories for parent and child folders up decided by user[default= ./] up to depth input by user (default = 2)
 		Usage: `beforeIgo [folder] [depth]` or `gitUpdate -f/--folder [folder] -d/--depth [depth]`
