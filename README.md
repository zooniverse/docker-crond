# docker-crond

This runs `crond` in Alpine. Place your crontab in `/etc/crontabs/` with the
name of a user in the system, e.g.:

- `/etc/crontabs/root`
- `/etc/crontabs/nobody`

Or put a script in one of the directories under `/etc/periodic/` (assuming you
don't also overwrite the default root crontab):

- `/etc/periodic/15min/`
- `/etc/periodic/daily/`
- `/etc/periodic/hourly/`
- `/etc/periodic/monthly/`
- `/etc/periodic/weekly/`
