# ScopeTech notes

## Build the image

```bash
cd ~/src/scopetech/openstreetmap-tile-server
# did not work without sudo on wsl2
sudo docker build -t openstreetmap-tile-server:dev --build-arg PG_VERSION=14 .
```
