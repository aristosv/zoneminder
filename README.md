# zoneminder
Automated installation of Zoneminder CCTV software in a containerized environment

Run the command below on a clean, minimal installation of Debian Buster.
```
bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/aristosv/zoneminder/master/zoneminder)
```

After the installation you can access Zoneminder on http://<ip_address>/zm/

To manage the zoneminder and mariadb containers you can use portainer
```
Name: portainer
Usage: docker container management
URL: http://<your_ip_here>:9000
```
