# Lab inventory

Cisco DevNet sandbox: IOS XE on Catalyst 8000v (on-demand, needs VPN)

| Hostname | IP address  | OS     | Platform          | Netmiko device_type |
|----------|-------------|--------|-------------------|---------------------|
| cat8kv   | 10.10.20.48 | IOS XE | Catalyst 8000v    | cisco_xe            |
| xrv9k    | 10.10.20.35 | IOS XR | IOS XRv 9000      | cisco_xr            |
| nx9k     | 10.10.20.40 | NX-OS  | Nexus 9000v       | cisco_nxos          |

Username: developer
Password: not stored here. It goes in an environment variable later.

Ports on cat8kv: 22 SSH, 830 NETCONF, 443 RESTCONF