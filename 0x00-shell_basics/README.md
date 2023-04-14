#!/bin/bash This is a shebang line specifying that this script should be interpreted using the Bash shell.
currentWorkingDirectory=$(realpath $(pwd)) i used 2 commands first one is pwd that tells the current working directory 
, and the realpath command that retrieves the absolute path of the directory,
The $() syntax is used to retieve the output of the commands in it and assign it to the currentWorkingDirectory variable.
