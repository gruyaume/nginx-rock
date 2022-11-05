# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:nginx_1.23.2_amd64.rock docker-daemon:nginx:1.23.2
docker run nginx:1.23.2
```
