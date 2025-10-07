# Linux Ubuntu
```console
sudo nano /etc/systemd/system/monthly-reboot.service
```
```console
sudo nano /etc/systemd/system/monthly-reboot.timer
```
```console
sudo systemctl daemon-reload
sudo systemctl enable monthly-reboot.timer
sudo systemctl start monthly-reboot.timer
```
```console
systemctl list-timers monthly-reboot.timer
```
