# Ubuntu 22 & Debian 12
**1. During installation if you encounter messages like "Pending kernel upgrade" or "Daemons using outdated libraries" or blah blah, just hit "Enter" to continue!**

**2. You can use port number 7301 or 7302 instead of default 7300**
```shell
wget https://raw.githubusercontent.com/virtualos/BadVPN/master/badvpn && bash badvpn
```
& reboot

To check port listening:
```shell
sudo lsof -i -P -n | grep LISTEN
```
