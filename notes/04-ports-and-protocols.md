# Ports and Protocols

## What is a protocol?

A protocol is a set of rules that devices use to communicate.

Examples:

- HTTP
- HTTPS
- DNS
- FTP
- SSH
- SMTP

## What is a port?

A port is a logical number used to identify a specific service running on a device.

Example:

```text
192.168.1.10:443
```

In this example, `443` is the port number.

## Common ports

| Port | Protocol/Service | Purpose |
|---|---|---|
| 20/21 | FTP | File transfer |
| 22 | SSH | Secure remote login |
| 23 | Telnet | Insecure remote login |
| 25 | SMTP | Sending email |
| 53 | DNS | Domain name resolution |
| 80 | HTTP | Web traffic |
| 110 | POP3 | Receiving email |
| 143 | IMAP | Receiving email |
| 443 | HTTPS | Secure web traffic |
| 3389 | RDP | Remote desktop |

## TCP vs UDP

| Feature | TCP | UDP |
|---|---|---|
| Connection | Connection-oriented | Connectionless |
| Reliability | More reliable | Less reliable |
| Speed | Slower | Faster |
| Examples | HTTP, HTTPS, SSH | DNS, streaming, VoIP |

## Why ports matter in cybersecurity

Open ports can reveal what services are running on a system. Attackers and defenders both analyze ports to understand network exposure.

Example:

```text
Port 22 open -> SSH may be running
Port 80 open -> Web server may be running
Port 3389 open -> Remote Desktop may be running
```

## Quick summary

- Protocols define communication rules.
- Ports identify services on a device.
- TCP focuses on reliability.
- UDP focuses on speed.
- Open ports are important during security analysis.
