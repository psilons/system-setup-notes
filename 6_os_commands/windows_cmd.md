# Windows Commands

## Key Shortcuts
Sourced from [Here](https://www.makeuseof.com/tag/ultimate-windows-10-shortcuts-gestures-collection/)  

Windows key + tab -> show open windows  
Windows key + I (cap i)-> settings  
Windows key + A -> actions  
Windows key + D -> show desktop  
Windows key + X -> power control  
Windows key + E -> windows file explorer  
Windows key + Pause/Break -> system  


## Windows Commands
- To add shortcuts to Windows menu, put them in 
  ```C:\Users\Wonderland\AppData\Roaming\Microsoft\Windows\Start Menu\Programs```
- Use Settings > Apps > Default apps to change file associations.
- Windows 10 has built-in tar command. Or we can use powershell to zip/unzip:
  ```
  powershell Compress-Archive <source> <target.zip>
  
  powershell expand-archive <source.zip> <target dir>
  ```
- find windows product key:
  ```
  wmic path softwarelicensingservice get OA3xOriginalProductKey
  ```

## Disk Tools
- Use [mklink](https://windows7home.net/how-to-create-symbolic-link-in-windows-7/)
  to create symbolic links 
- Use fsutil to find out symbolic link status
  ```
  fsutil behavior query SymlinkEvaluation
  
  Local to local symbolic links are enabled.
  Local to remote symbolic links are enabled.
  Remote to local symbolic links are disabled.
  Remote to remote symbolic links are disabled.
  ```

## Network

### IP tracing
- `ping <IP> -t`
Tracert <IP>
Tracert -h 5 google.com  # limit hop count

Nslookup <IP>

Netstat
Netstat -n 5 # interval

Arp -a <IP> # get mac address

Route print

Route -f 

Netsh /?

Netsh winsock reset


Netsh -c interface dump ><filename>
### ipconfig
- `ipconfig`
- `ifconfig -a` on Linux, ether 00 address is the MAC address
- `ipconfig/all` on Windows, "Physical Address" is the MAC address
- 
- `ipconfig/release`
- `ipconfig/renew`
- 
- `ipconfig/flushdns`

### HTTP
To check network http proxy

```netsh winhttp show proxy```

The output is similar to this:
```
Current WinHTTP proxy settings:

    Direct access (no proxy server).
```
or
```
Current WinHTTP proxy settings:

    Proxy Server(s) :  89.42.198.79:47570
    Bypass List     :  (none)
```

## Processes
To find which PID uses a given port
```
netstat -aon | findstr 57603
  Proto  Local Address          Foreign Address        State           PID
  TCP    127.0.0.1:57603        127.0.0.1:57604        ESTABLISHED     13760
  TCP    127.0.0.1:57604        127.0.0.1:57603        ESTABLISHED     13760
```
To find executable by PID
```
tasklist | findstr 13760
Image Name                     PID Session Name        Session#    Mem Usage
========================= ======== ================ =========== ============
firefox.exe                  13760 Console                    1    734,072 K
```

To flush DNS
```
ipconfig /flushdns
```
