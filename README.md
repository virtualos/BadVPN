# Ubuntu 22 & Debian 12
**1. During installation if you encounter messages like "Pending kernel upgrade" or "Daemons using outdated libraries" or blah blah, just hit "Enter" to continue!**

**2. Default port is 7302**
```shell
wget https://raw.githubusercontent.com/virtualos/BadVPN/master/badvpn && bash badvpn
```
3. Afterwards **reboot** server.

4. To check port listening:
```shell
sudo lsof -i -P -n | grep LISTEN
```
