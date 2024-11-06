# Powerinfo
Reports battery info to the user.
Supports raw values.

## Dependencies
* Any standard POSIX shell
* bc (Basic Calculator), any version.
for more detailed and technical dependencies, take a look at DOCS/DEPENDENCIES.

## Configuration and usage
For information about configuration and usage please take a look at the DOCS file, containing almost all documentation.
Alternatively look in `man powerinfo` for instructions on how to use it.
Or run `powerinfo -h` to get to the help page.
### Installation
1. Clone the repository and `cd` into it
```
$ git clone https://github.com/CrasyCookie/powerinfo && cd powerinfo
```
2. Run the `install` script as a superuser (root).
```
# ./install -imu
```
You can look at the possible install flags with
```
$ ./install -h
```
### Updating/Upgrading
If you installed it with -s (symlink) enabled, then run
```
# ./install -u
```
If you installed it without -s enabled, run
```
# ./install -imu
```
You can read about the flags with `./install -h`.
