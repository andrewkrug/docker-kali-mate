#Readme

This container inherits the base container from docker-kali-rolling.

#The container includes the following:

* Kali Linux Top 10
* Mate Desktop
* Spice Server

To use this container if you don't want to build it yourself.

1. `docker pull andrewkrug/kali-linux-mate:rolling`
2. `docker run -p 5900:5900 andrewkrug/kali-linux-mate:rolling`
3. Ensure the installation of a spice client. `apt-get install spice-client-gtk`
4. Connect to the Spice listener on the container. `spicy -h localhost -p 5900`  
