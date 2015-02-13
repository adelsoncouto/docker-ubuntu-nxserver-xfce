docker-ubuntu-vnc-desktop
=========================

### From Docker Index
```
docker pull ensky/docker-ubuntu-nxserver-xfce
```

### Build yourself
```
git clone https://github.com/ensky/docker-ubuntu-nxserver-xfce.git
docker build --rm -t ensky/docker-ubuntu-nxserver-xfce docker-ubuntu-nxserver-xfce
```

### Run
```
docker run -d -p 222:22 -v /etc:/mnt:ro -v /home:/home:rw ensky/docker-ubuntu-nxserver-xfce
```

### SSH
```
ssh your_system_account@localhost -p 222
```

### ([http://nx-client-for-windows.software.informer.com/3.5/](NX client))
use NX Client to connect to your server.

choose UNIX -> CDE as your desktop setting in NX Client.

### reference
+ [https://help.ubuntu.com/community/FreeNX](FreeNX)