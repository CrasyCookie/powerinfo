# Powerinfo
Simply reads info about the battery and reports back to the user.
Supports showing raw values.

## Dependencies
* Any standard UNIX-like/POSIX shell
* bc (Basic Calculator)

## TODO
* Add flags to control output
* Make it into multiple symlinks pointing to the file and use `$0` to apply flags correctly based off that, like busybox does it.
* Find out the difference between `charge_...._threshold` and `charge_control_...._threshold`

## Flags (to be implemented)
`-R`              Raw output, only output values like `80%` and `48.2/57.0`.
`-c CONFIG`       Point to an alternate configuration file.
`-e`              Ignore errors and just warn the user instead.
`-E`              Ignore errors silently.
