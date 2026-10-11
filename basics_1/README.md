# Networking Basics 1

This project covers basic networking concepts in Ubuntu.

## Learning Objectives

By the end of this project, I should be able to explain:

- What `localhost` and `127.0.0.1` are
- What `0.0.0.0` means
- What the `/etc/hosts` file is used for
- How to display active network interfaces

## Requirements

- All scripts are written for Ubuntu 22.04
- All Bash scripts start with:

```bash
#!/usr/bin/env bash
```

- The second line of each script contains a comment explaining what the script does
- All Bash scripts are executable
- All files end with a new line
- Scripts must pass Shellcheck without errors

## Task 0 - Change Your Home IP

The `0-change_your_home_IP` script modifies the `/etc/hosts` file so that:

- `localhost` resolves to `127.0.0.2`
- `facebook.com` resolves to `8.8.8.8`

The script must be executed with `sudo` because `/etc/hosts` is a system file.

Example:

```bash
sudo ./0-change_your_home_IP
```
