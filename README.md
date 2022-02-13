# nCube-MUV
Start Guide

### Install dependencies
```
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -

$ sudo apt-get install -y nodejs

$ node -v

$ sudo npm install -g pm2

$ git clone https://github.com/IoTKETI/nCube-MUV

$ cd /home/pi/nCube-MUV

$ npm install
```

### Install MQTT-broker
```
$ wget http://repo.mosquitto.org/debian/mosquitto-repo.gpg.key
$ sudo apt-key add mosquitto-repo.gpg.key
$ cd /etc/apt/sources.list.d/
$ sudo wget http://repo.mosquitto.org/debian/mosquitto-buster.list 
$ sudo apt-get update
$ sudo apt-get install -y mosquitto
```
[Adobe Scan 2022년 2월 13일.pdf](https://github.com/sang9n/cssrj/files/8055179/Adobe.Scan.2022.2.13.pdf)
