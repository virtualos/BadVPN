# Ubuntu & Debian
**During installation if you encounter messages like "Pending kernel upgrade" or "Daemons using outdated libraries" or blah blah, just hit "Enter" to continue!**
```shell
sudo apt update && sudo apt upgrade -y && wget https://raw.githubusercontent.com/virtualos/BadVPN/master/badvpn && bash badvpn
```
reboot the server!


To check port 7300 is listening:
```shell
sudo lsof -i -P -n | grep LISTEN
```
