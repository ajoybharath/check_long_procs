# check_long_procs

Nagios Plugin for checking long running processes

Uses `ps` command to determine process durations,

and alerts if the process is running for more than 24 hours

All the values are tunable,

Say for eg:- only the processes which are running for more than '36' hours

It can take multiple process names as search patterns

The process names are passed as arguments to the script