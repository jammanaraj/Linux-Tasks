
sudo docker save -o ng.tar nginx:latest

moving tar file to 20.55.67.19 server to location /home/vm1
> scp -r /home/vm/ng.tar vm1@20.55.67.190:/home/vm1
