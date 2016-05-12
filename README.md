# standup-notification

## First you have to install libasound on the Raspberry Pi 
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