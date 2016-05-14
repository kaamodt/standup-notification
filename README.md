# standup-notification

## Install libasound on the Raspberry Pi 
sudo apt-get update 
sudo apt-get install libasound2-dev

### sound set to Analog output
amixer cset numid=3 1

### sound set to HDMI
amixer cset numid=3 2

### sound set volume
alsamixer

## Setup of app
* npm install

## Run
* npm start
* Set the Watson T2S credentials in the Watson T2S node

## Futures Potential
* Implement iBeacon detection of team members in room
* Make it platform independant (use browser instead of OS sound lib)
