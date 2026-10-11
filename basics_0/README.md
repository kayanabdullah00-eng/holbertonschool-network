# Networking Basics #0

## Description

This project introduces the fundamental concepts of computer networking.

The main topics covered include:

- The OSI Model
- LAN and WAN networks
- The Internet
- IP addresses
- IPv4 and IPv6
- Localhost
- Subnets
- TCP and UDP protocols
- Network ports
- ICMP
- Common networking tools and commands

The goal of this project is to understand how computers communicate over networks and how the different networking layers and protocols work together.

## Learning Objectives

By the end of this project, I should be able to explain:

### OSI Model

- What the OSI model is
- The seven layers of the OSI model
- How the layers are organized
- The purpose of the Network and Transport layers

### LAN

- What a LAN is
- Typical LAN usage
- The geographical size of a LAN

### WAN

- What a WAN is
- Typical WAN usage
- The geographical size of a WAN

### Internet

- What the Internet is
- What an IP address is
- The difference between IPv4 and IPv6
- What localhost is
- What a subnet is
- Why IPv6 was created

### TCP and UDP

- What TCP is
- What UDP is
- The main differences between TCP and UDP
- What a network port is
- Common port numbers

Important ports:

- SSH: `22`
- HTTP: `80`
- HTTPS: `443`

### ICMP

ICMP stands for Internet Control Message Protocol.

It is commonly used for network diagnostics.

The `ping` command uses ICMP to check whether another device is reachable over a network.

## OSI Model Layers

The OSI model contains seven layers:

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

The layers are organized from the lowest level, which deals with physical transmission, to the highest level, which interacts with applications.

## Requirements

- All scripts are interpreted on Ubuntu 22.04.
- Bash scripts must start with:

```bash
#!/usr/bin/env bash
```

- The second line of each Bash script must contain a comment describing what the script does.
- All files must end with a new line.
- Bash scripts must be executable.
- Bash scripts must pass `shellcheck` without errors.
- A `README.md` file is required at the root of the project directory.

## Repository

GitHub repository:

`holbertonschool-network`

Project directory:

`basics_0`

## Files

The project contains answer files and Bash scripts related to networking fundamentals.

Example:

`0-OSI_model`

This file contains the answers to questions about the OSI model.

## Author

Kayan Alnazari
