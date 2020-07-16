# Networking

### Important

- Checking routing tables
  - Linux: `ip route`
  - Windows: `route print`
  - MacOS: `netstat -r`
- Check MAC addresses
  - Windows: `ipconfig /all`
  - Linux/MacOS: `ifconfig`
  - Linux: `ip addr`
- Check ARP cache
  - WIndows: `arp -a`
  - MacOS/Linux: `arp`
  - Linux: `ip neighbour`
- Common ports
  - 25 - SMTP
  - 22 - SSH
  - 110 - POP3
  - 143 - IMAP
  - 80 - HTTP
  - 443 - HTTPS
  - 137, 138, 139 - NETBIOS
  - 115 - SFTP
  - 23 - Telnet
  - 21 - FTP
  - 3389 - RDP
  - 3306 - MySQL
  - 1433 - MS SQL Server
- Check listening ports
  - Windows: `netstat -ano`
  - Linux: `netstat -tunp`
  - MacOS: `netstat -p tcp -p udp; lsof -n -i4TCP -i4UDP`
- 