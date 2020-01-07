# pi-shutdown

Trigger Raspberry Pi shutdown with GPIO push button.

## Remove the systemd service

```
$ sudo systemctl stop pi-shutdown
$ sudo systemctl disable pi-shutdown
$ sudo systemctl daemon-reload
$ sudo rm /etc/systemd/system/pi-shutdown.py /etc/systemd/system/pi-shutdown.service
```