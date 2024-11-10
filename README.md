# Dummy Systemd Service

This project sets up a basic systemd service that runs a script in the background. The script simulates an application by logging a message every 10 seconds.

## Requirements

- Linux-based system (Ubuntu preferred)
- root access to install and configure systemd services

## Project URL

[Dummy Systemd Service - Roadmap](https://roadmap.sh/projects/dummy-systemd-service)

## Files

1. `dummy.sh`: A script that runs indefinitely and logs a message every 10 seconds to `/var/log/dummy-service.log`.
2. `dummy.service`: A systemd service configuration to run the `dummy.sh` script automatically on boot and keep it running in the background.
