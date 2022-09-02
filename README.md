To use (with a MacBook):

image an SD card with: sudo dd bs=1m if=~/Downloads/2022-04-04-raspios-buster-armhf-lite.img of=/dev/disk2

sudo apt update -y && sudo apt-get upgrade -y

sudo apt install git ansible -y

To Use: ansible-pull -d /home/pi/pull -i 'localhost,' -U https://github.com/Wied58/pull_oled_setup_from_git pull_oled_setup_from_git.yml

To test: /home/pi/Adafruit_Python_SSD1306/examples/python3 stats.py

For extra credit (send to process background): /home/pi/Adafruit_Python_SSD1306/examples/python3 stats.py & 

