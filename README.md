# Powerinfo
Reports battery info to the user.
Supports raw values.

## Dependencies
* Any standard UNIX-like/POSIX shell
* bc (Basic Calculator)

## TODO
* Finish adding flags to use in output
* Base output on set flags

## Flags (more to be added)
### Output flags
`-c`              Include battery cycles in output.
`-p`              Include battery charge percentage in output.
`-s`              Include the charging status in output (Charging/Discharging).
`-t`              Include set charging thresholds in output.
`-w`              Include current charge out of the maximum charge in output.
`-W`              Include maximum charge out of design maximum charge in output.

### Control flags
`-C CONFIG`       Point to an alternate configuration file.
`-e`              Ignore errors and just warn the user instead.
`-E`              Ignore errors silently.
`-R`              Raw output, only output values like `80%` and `48.2Wh/57.0Wh`.
