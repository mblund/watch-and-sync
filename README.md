# watch-and-sync

This is a script to automatically synchronize a local project folder to a
remote server. It watches the local folder for changes and recreates the 
local state on the target machine as soon as a change is detected. The 
script will ignore files according to .gitignore 

Usage:

watch-and-sync /local/path remote /remote/server/path

Warning: Remote path will be overwritten with local version if differences occur!!!

Dependencies:
fswatch - fswatch is used to detect file changes. (brew install fswatch)




