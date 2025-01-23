# [MJT Services](https://github.com/mjt-services) Service Monitor 2025

- monitors active services to ensure uptime
- configuration as code
- CLI for managing, starting, stopping, inspecting, etc...
- observability for service processes
  - logs
  - GUI for charting and overview


# How
- SSH for remote control
- TypeScript for the code
- Docker for containerization of this meta-service
- Sqlite for the database(s) (logs and configuration)

## Access the commands

```bash
$ . SOURCE_ME.sh
```

## Commands

| Command | Description         |
| ------- | ------------------- |
| `up`    | Starts the services |