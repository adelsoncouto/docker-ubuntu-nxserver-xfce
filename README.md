docker-ubuntu-nxserver-xfce
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

### ([NX client](http://nx-client-for-windows.software.informer.com/3.5/))
use NX Client to connect to your server.

choose UNIX -> CDE as your desktop setting in NX Client.

### reference
+ [Registry Repository site](https://registry.hub.docker.com/u/ensky/docker-ubuntu-nxserver-xfce/)
+ [FreeNX](https://help.ubuntu.com/community/FreeNX)
