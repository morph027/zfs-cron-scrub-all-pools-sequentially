# ZFS cron scrub

This script can be used by e.g. _cron.monthly_ to sequentially check all zfs pools. A time range can be set with the variables _SECONDS_ and _MULTIPLIER_. Mine is set to 3 months.

## Parameters

* ```-e|--exclude```: takes a comma sep. list of pools to exclude from scrub
* ```-s|--skip-by-timerange```: enable skipping by time range
