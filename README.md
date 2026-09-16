# server-check

A lightweight, read-only command-line tool for checking basic Linux server health information.

## Features

`server-check` provides a quick overview of common system conditions:

- Hostname
- Operating system
- System uptime
- Root filesystem usage
- Memory information
- Load average
- Failed systemd units

The tool is intentionally simple and performs read-only checks. It does not modify system configuration or restart services.

## Installation

Once the Snap package is published, install it with:

```bash
sudo snap install server-check
