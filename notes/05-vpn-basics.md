# VPN Basics

## What is a VPN?

VPN stands for Virtual Private Network. It creates an encrypted connection between a device and a VPN server.

## Why VPNs are used

VPNs are commonly used to:

- Secure internet traffic on public Wi-Fi
- Connect employees to company networks remotely
- Hide traffic from local network observers
- Access internal resources securely

## Basic VPN flow

```mermaid
flowchart LR
    A[User Device] --> B[Encrypted VPN Tunnel]
    B --> C[VPN Server]
    C --> D[Internet or Private Network]
```

## VPN tunnel

A VPN tunnel is the encrypted path between the user's device and the VPN server.

## Common VPN protocols

| Protocol | Notes |
|---|---|
| OpenVPN | Popular and widely supported |
| WireGuard | Modern, fast, and lightweight |
| IPsec/IKEv2 | Common in enterprise environments |
| L2TP/IPsec | Older but still used in some setups |

## VPN limitations

A VPN improves privacy and security, but it does not make a user completely anonymous or fully protected from all threats.

A VPN does not replace:

- Strong passwords
- Multi-factor authentication
- Safe browsing habits
- Endpoint security
- Patch management

## Quick summary

- VPNs create encrypted connections.
- They are useful for remote access and safer browsing.
- VPNs improve privacy but do not solve every security problem.
