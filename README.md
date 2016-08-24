# coreos-timer-clean

**Use shell in service file**

The [https://github.com/shenshouer/docker-clean](go version in docker)

put all unit files to /etc/systemd/system/ on CoreOS

```
systemctl daemon-reload 

systemctl start start-clean-none-docker-image.timer && systemctl start stop-clean-none-docker-image.timer

systemctl enable start-clean-none-docker-image.timer && systemctl enable stop-clean-none-docker-image.timer 
```