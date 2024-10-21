- __```cat /etc/os-release```__
- __```cat /etc/passwd| column -t -s :``` or ```cat /etc/passwd```__
- __```cat /etc/group```__

### Login information
- __In the `/var/log` directory, we can find log files of all kinds including `wtmp` and `btmp`. The `btmp` file saves information about failed logins, while the `wtmp` keeps historical data of logins.__