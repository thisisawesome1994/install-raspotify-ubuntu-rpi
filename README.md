# install-raspotify-ubuntu-rpi
Install raspotify on raspberry pi4 running Ubuntu server 20.04

Run the following commands:

sudo apt update && sudo apt upgrade -y
sudo dpkg --add-architecture armhf
cd ~
apt update
wget https://dtcooper.github.io/raspotify/raspotify-latest.deb
sudo apt install libasound2
dpkg -i raspotify-latest.deb
sudo apt --fix-broken install
