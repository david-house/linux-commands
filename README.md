# linux-commands
Short commands for Linux, Raspberry Pi, etc.

## Ports

### Show listening ports
 ```sudo netstat -tulpn | grep LISTEN```
 
## GPS

### Start GPSD from command line
```sudo gpsd /dev/ttyACM0 -n -F /var/run/gpsd.sock```
*Note the -n flag tells gpsd to poll continuously, even when there is no client listening. To me it seems more stable when you have multiple clients and lots of connection activity. YMMV*

