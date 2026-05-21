# Common Networking Commands Cheat Sheet

## Windows

| Command | Purpose |
|---|---|
| `ipconfig` | View IP configuration |
| `ipconfig /all` | View detailed network settings |
| `ipconfig /release` | Release current DHCP address |
| `ipconfig /renew` | Request new DHCP address |
| `ipconfig /flushdns` | Clear DNS cache |
| `ping example.com` | Test connectivity |
| `tracert example.com` | Trace route to destination |
| `nslookup example.com` | Check DNS resolution |
| `netstat -ano` | View active connections and ports |

## Linux/macOS

| Command | Purpose |
|---|---|
| `ip addr` | View IP addresses |
| `ifconfig` | View network interfaces |
| `ping example.com` | Test connectivity |
| `traceroute example.com` | Trace route to destination |
| `dig example.com` | Query DNS records |
| `nslookup example.com` | Check DNS resolution |
| `ss -tuln` | View listening TCP/UDP ports |
| `curl https://example.com` | Test web requests |
| `wget https://example.com` | Download or test a URL |

## Practice tasks

Try these in a safe lab or personal system:

1. Find your private IP address.
2. Find your default gateway.
3. Ping your router.
4. Resolve a domain name using DNS.
5. Check which ports are listening on your system.
6. Use `curl` to view response headers from a website.
