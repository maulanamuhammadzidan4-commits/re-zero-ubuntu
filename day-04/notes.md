# Day 4 - Basic Networking
## Daily Target
- Learn about networking in Linux.

## What I learned today
1. IP address
2. Port

### IP address
IP address is a unique identifier for a device on a network. To check ip address in linux, use `ip a` command.  

local address: `127.0.0.1` (localhost)  

use `ping <ip-address>` for checking if the device is reachable.  

### Port
PORT is a number that is used to identify a service on a device. To check port in linux, use `ss -tulpn` command.   

Common ports:
- 22: SSH
- 80 or 8080: HTTP / PHP / NGIX / APACHE
- 443: HTTPS
- 3306: MYSQL

Use `curl http://localhost` for checking if http is running.

### Troubleshooting
-

### Screenshots
![Documentation1](../screenshots/day-4-01.png)
![Documentation2](../screenshots/day-4-02.png)
![Documentation3](../screenshots/day-4-03.png)
![Documentation4](../screenshots/day-4-04.png)
![Documentation5](../screenshots/day-4-05.png)
![Documentation6](../screenshots/day-4-06.png)