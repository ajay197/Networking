# Networking

### Change Password

> net user

> net user user_name password

> net user user_name *

### Activate Administrator account

Cmd as Admin

> net user administrator /active:yes

> net user administrator password

### Check Active members on PC

> net view

### Block websites

ctrl + R > %windir%\System32\drivers\etc

open hosts file in notepad

add websites > 127.0.0.2       website_name

### Get Wifi password

> netsh wlan show profile wifi_name key=clear

### Access blocked websites

Goto proxysite.com and enter website

### Get ip address of any website

> ping facebook.com

### Shutdown/Restart remote PC

Open Cmd as Admin

> netstat   ->to get IP address of victim

> shutdown -i

Add IP address or victim name

> shutdown -a  ->to stop shutdown

