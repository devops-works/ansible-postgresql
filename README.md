# ansible-postgresql

Installs PostgreSQL on Ubuntu and adds pgdump_all script. Backup script is running hourly.

## Requirements

None

## Role variables

- `psql_backup`: Boolean to activate backups (default: `true`)
- `psql_backup_dir`: Directory for backups (default: `/var/backups/psql`)
- `psql_backup_keep`: How many days of backups to keep on local filesystem (default : `7`)

## License

MIT

## Author

[Devops.works](https://www.devops.works)