Docker NFS Server
================

Usage
----
```bash
docker network create nfs-network
```

```bash
docker run -d --name nfs --network=nfs-network --privileged  nikkollaii/nfs-server 
```

```bash
docker run -d --name nfs-client  --network=nfs-network  --privileged  nikkollaii/nfs-client 
``` 
