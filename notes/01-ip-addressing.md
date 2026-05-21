# IP Addressing Basics

## What is an IP address?

An IP address is a unique address used to identify a device on a network. It allows devices to send and receive data.

Example IPv4 address:

```text
192.168.1.10
```

## IPv4 vs IPv6

| Type | Example | Notes |
|---|---|---|
| IPv4 | 192.168.1.10 | Most commonly seen format |
| IPv6 | 2001:0db8:85a3::8a2e:0370:7334 | Designed to support many more devices |

## Private IP addresses

Private IP addresses are used inside local networks such as home, office, or lab networks.

Common private ranges:

```text
10.0.0.0 - 10.255.255.255
172.16.0.0 - 172.31.255.255
192.168.0.0 - 192.168.255.255
```

## Public IP addresses

A public IP address is used on the internet. Your router usually has a public IP address assigned by your internet service provider.

## Static vs dynamic IP

| Type | Meaning |
|---|---|
| Static IP | Manually assigned and does not usually change |
| Dynamic IP | Automatically assigned, usually by DHCP |

## DHCP

DHCP stands for Dynamic Host Configuration Protocol. It automatically gives devices network settings such as:

- IP address
- Subnet mask
- Default gateway
- DNS server

## Default gateway

A default gateway is usually the router. It forwards traffic from your local network to other networks, including the internet.

## Subnet mask

A subnet mask separates the network part and host part of an IP address.

Example:

```text
IP address:   192.168.1.10
Subnet mask:  255.255.255.0
Network:      192.168.1.0
```

## Quick summary

- IP addresses identify devices.
- Private IPs are used inside local networks.
- Public IPs are used on the internet.
- DHCP automatically assigns IP settings.
- The default gateway helps devices reach other networks.
