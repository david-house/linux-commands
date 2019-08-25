# linux-commands
Short commands for Linux, Raspberry Pi, etc.

## Ports

### Show listening ports
 ```sudo netstat -tulpn | grep LISTEN```
 
## GPS

### Start GPSD from command line
```sudo gpsd /dev/ttyACM0 -F /var/run/gpsd.sock```
