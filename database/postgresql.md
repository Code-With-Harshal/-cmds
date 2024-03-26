# PostgreSQL

## Windows

### Install PostgreSQL
[Windows installers](https://www.postgresql.org/download/windows/)
Download and follow the instructions of installer.

### Start Server
```sh
pg_ctl start -D "C:\Program Files\PostgreSQL\16\data"
```
### Start status
```sh
pg_ctl status -D "C:\Program Files\PostgreSQL\16\data"
```
### Start Restart
```sh
pg_ctl restart -D "C:\Program Files\PostgreSQL\16\data"
```
