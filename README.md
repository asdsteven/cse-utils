# cse-utils

`cse` is a bash script.  All other files just store strings to be read by `cse`, for string-matching html responses.  

```
Usage:
cse get <file>
        Download {user}@linux1:~/<file>
cse put <file>
        Upload {user}@linux1:~/<file>
cse print ps2 <file>
        Print {user}@linux1:~/<file> on ps2 printer
cse ssh
        ssh to {user}@linux1
cse ssh <command>
        Execute <command> on {user}@linux1
cse www <file>
        Upload <file> to {user}@linux1:~/www/ and enable read
        You can then visit the file on:
        http://appsrv.cse.cuhk.edu.hk/~{user}/<file>
cse vpn
        Show cse vpn status (on Mac)
        You should have already setup the VPN as "CSE VPN"
cse vpn on
        Connect cse vpn (on Mac)
cse vpn off
        Disconnect cse vpn (on Mac)
cse wifi
        Show wifi status (on Mac)
cse wifi on
        Turn on wifi (on Mac)
cse wifi off
        Turn off wifi (on Mac)
cse wifi erg
        Connect to ERGWAVE3 (on Mac)
cse wifi uni
        Connect to University WiFi (on Mac)
cse ergwave
        Login ERGWAVE3 (on Mac)
cse ergwave out
        Logout ERGWAVE3 (on Mac)
```
