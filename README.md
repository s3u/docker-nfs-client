Docker NFS Server
================

Usage
----
```bash
docker run -d --name nfs-server --privileged -v /home/docker/share:/home/share nfs-server
```

```bash
docker run -d --name nfs-client --privileged -e NFS_PORT_2049_TCP_ADDR=172.17.0.2 nfs-client
``` 
