# Ubuntu 22 & Debian 12
1. During installation if you encounter messages like "Pending kernel upgrade" or "Daemons using outdated libraries" or blah blah, **Just hit "Enter" to continue!**

2. UDPGW port is **7300**
```shell
wget https://raw.githubusercontent.com/virtualos/BadVPN/master/badvpn && bash badvpn
```
3. Afterwards **reboot** server.
_____________________________________________
To check port listening:
```shell
sudo lsof -i -P -n | grep LISTEN
```
