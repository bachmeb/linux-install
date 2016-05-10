# tigervnc

## References
* http://tigervnc.org/
* https://github.com/TigerVNC/tigervnc/releases
* https://github.com/TigerVNC/tigervnc/releases/tag/v1.6.0
* https://bintray.com/tigervnc/stable/tigervnc/1.6.0
* https://wiki.centos.org/HowTos/VNC-Server
* https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/7/html/System_Administrators_Guide/ch-TigerVNC.html
* https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Deployment_Guide/chap-TigerVNC.html


##### Search repo for vnc
```
yum search vnc
```

##### Install
```
sudo yum install tigervnc-server
```

##### Ask where is vncserver
```
whereis vncserver
```

##### Check the status of the service
```
sudo /sbin/service vncserver status
```
```c
/*
Xvnc is stopped
*/
```