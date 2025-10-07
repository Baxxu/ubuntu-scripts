# Linux Ubuntu
```console
sudo nano /etc/systemd/system/monthly-reboot.service

sudo nano /etc/systemd/system/monthly-reboot.timer

sudo systemctl daemon-reload
sudo systemctl enable monthly-reboot.timer
sudo systemctl start monthly-reboot.timer

systemctl list-timers monthly-reboot.timer
```
