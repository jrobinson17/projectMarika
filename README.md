docker-ubuntu-vnc-desktop
=========================
Rewritten by
James Robinson
JayR Tech Solutions LLC

From Docker Index
```
docker pull dorowu/ubuntu-desktop-lxde-vnc
```

Build yourself
```
git clone https://github.com/fcwu/docker-ubuntu-vnc-desktop.git
docker build --rm -t dorowu/ubuntu-desktop-lxde-vnc docker-ubuntu-vnc-desktop
```

Run
```
docker run -i -t -p 6080:6080 dorowu/ubuntu-desktop-lxde-vnc
```

Browse http://127.0.0.1:6080/vnc.html

<img src="https://raw.github.com/fcwu/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Trobleshooting
==================

1. boot2docker connection issue, https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/2


License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.
