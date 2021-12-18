# Useful Linux Commands

https://askubuntu.com/questions/1020692/terminal-splash-screen-with-weather-calendar-time-sysinfo

https://www.makeuseof.com/best-cli-tools-to-monitor-linux-performance-terminal/

## Network

First, `vi /etc/ssh/sshd_config` to change  
`PasswordAuthentication Yes`  
Then  
`service sshd restart`

Next, `vi ifcfg-enth1` to set
```
GATEWAY=192.168.56.1
DNS1=114.114.114.114
DNS2=8.8.8.8
```
Then  
`service network restart`


