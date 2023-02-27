## fc00-SSH
```sh
docker commit <CONTAINER> 127.0.0.1:1027/fc00/ubuntu/ssh:lunar-20221216
docker run --name ssh -v /root:/mnt -ti 127.0.0.1:1027/fc00/ubuntu/ssh:lunar-20221216
apt update
apt upgrade -y
apt install ssh -y
```
###

## fc00-SSH2
https://docker-docs.uclv.cu/engine/examples/running_ssh_service/
