#### Enumeration

```
sudo nmap -Pn -p- -sV 192.168.239.140 -T4 -oN Hepet.nmap
```

```
Host discovery disabled (-Pn). All addresses will be marked 'up' and scan times will be slower.
Starting Nmap 7.91 ( https://nmap.org ) at 2021-08-16 11:19 EDT
Nmap scan report for 192.168.239.140
Host is up (0.21s latency).
Not shown: 65522 filtered ports
PORT      STATE SERVICE        VERSION
25/tcp    open  smtp           Mercury/32 smtpd (Mail server account Maiser)
79/tcp    open  finger         Mercury/32 fingerd
105/tcp   open  ph-addressbook Mercury/32 PH addressbook server
106/tcp   open  pop3pw         Mercury/32 poppass service
110/tcp   open  pop3           Mercury/32 pop3d
143/tcp   open  imap           Mercury/32 imapd 4.62
443/tcp   open  ssl/http       Apache httpd 2.4.46 ((Win64) OpenSSL/1.1.1g PHP/7.3.23)
2224/tcp  open  http           Mercury/32 httpd
7680/tcp  open  pando-pub?
8000/tcp  open  http           Apache httpd 2.4.46 ((Win64) OpenSSL/1.1.1g PHP/7.3.23)
11100/tcp open  vnc            VNC (protocol 3.8)
20001/tcp open  ftp            FileZilla ftpd 0.9.41 beta
33006/tcp open  unknown
1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at https://nmap.org/cgi-bin/submit.cgi?new-service :
SF-Port33006-TCP:V=7.91%I=7%D=8/16%Time=611A82E9%P=x86_64-pc-linux-gnu%r(N
SF:ULL,4D,"I\0\0\x01\xffj\x04Host\x20'192\.168\.49\.239'\x20is\x20not\x20a
SF:llowed\x20to\x20connect\x20to\x20this\x20MariaDB\x20server")%r(RPCCheck
SF:,4D,"I\0\0\x01\xffj\x04Host\x20'192\.168\.49\.239'\x20is\x20not\x20allo
SF:wed\x20to\x20connect\x20to\x20this\x20MariaDB\x20server")%r(LANDesk-RC,
SF:4D,"I\0\0\x01\xffj\x04Host\x20'192\.168\.49\.239'\x20is\x20not\x20allow
SF:ed\x20to\x20connect\x20to\x20this\x20MariaDB\x20server")%r(afp,4D,"I\0\
SF:0\x01\xffj\x04Host\x20'192\.168\.49\.239'\x20is\x20not\x20allowed\x20to
SF:\x20connect\x20to\x20this\x20MariaDB\x20server");
Service Info: Host: localhost; OS: Windows; CPE: cpe:/o:microsoft:windows

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 294.07 seconds
```