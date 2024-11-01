# Powerinfo
Reports battery info to the user.
Supports raw values.

## Dependencies
* Any standard UNIX-like/POSIX shell<sub> note that powerinfo does not use any bashisms</sub>
* bc (Basic Calculator)

## Configuration and usage
For information about configuration and usage please take a look at the DOCS file, containing all necessary information about powerinfo.
## Installation
Firstly clone the repository somewhere and cd into it.
To "install" it, you can make a symbolic link into `/usr/local/bin/` with  
`sudo ln --symbolic --target-directory=/usr/local/bin/ "$(pwd)"/powerinfo`  
or you can just copy the file to `/usr/local/bin/`.
