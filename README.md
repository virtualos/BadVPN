# Ubuntu & Debian
**1. During installation if you encounter messages like "Pending kernel upgrade" or "Daemons using outdated libraries" or blah blah, just hit "Enter" to continue!**

**2. You can select port number 7301 or 7302 instead of default 7300**
```shell
wget https://raw.githubusercontent.com/virtualos/BadVPN/master/badvpn && bash badvpn
```

To check port 7300 is listening:
```shell
sudo lsof -i -P -n | grep LISTEN
```
