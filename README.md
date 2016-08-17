# coreos-timer-clean

**Use shell in service file**

put all unit files to /etc/systemd/system/ on CoreOS

```
systemctl daemon-reload 

systemctl start start-clean-none-docker-image.timer && systemctl start stop-clean-none-docker-image.timer

systemctl enable start-clean-none-docker-image.timer && systemctl enable stop-clean-none-docker-image.timer 
```