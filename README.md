# rtl8192eu
Driver TPLINK TL-WN8200ND

sudo apt-get install git dkms git make build-essential
cd /usr/src
sudo git clone https://github.com/lwfinger/rtl8188eu.git
sudo dkms add ./rtl8188eu
sudo dkms build 8188eu/1.0
sudo dkms install 8188eu/1.0
sudo modprobe 8188eu

https://askubuntu.com/questions/619840/rtl8192eu-driver-does-not-work
