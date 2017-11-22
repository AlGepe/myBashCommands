# Custom Bash Commands

Collection of bash commands created by me to achieve extra functionality or simplify tasks

## Usage:

Add: export PATH=$PATH":path/to/folder" to [.bashrc] file and change permissions on executable files [chmod +x fileName]

For spotify shortcut wmctrl is needed [sudo apt install wmctrl] and spoti script must be placed in /usr/bin/

## newRepo $1 $2

Creates a new github repository with name $1 for user $2. $2 is optional and deafults to AlGepe (me).

## spoti

Checks if Spotify is opened to then open it (if not open) or bring window to front (if already open)

## updateWork

Updates git repositories for current and child folders up to depth input by user (default = 2)
