# goormide-init

This is my goormide container setup script
This script will update ubuntu version, install nodejs latest and install cloudflared tunnel

Due to very unclear goormide's env. I need script that can automate installing and this script is what i made

Install:

```sh
curl https://raw.githubusercontent.com/qwreey/goormide-init/master/cloudinit -o /etc/init.d/cloudinit; chmod u+x /etc/init.d/cloudinit; /etc/init.d/cloudinit
```

