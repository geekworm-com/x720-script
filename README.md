# x720-script
Shell script for X720, include safe shutdown and real time clock script.

NOTE:

We test this shell script base official Raspbian '2018-11-13-raspbian-stretch.img' version;

How to use?

step 1:
wget https://raw.githubusercontent.com/geekworm-com/x720-script/master/x720.sh

sudo chmod +x x720.sh

sudo bash x720.sh

step 2:
printf "%s\n" "alias x720off='sudo x720shutdown.sh'" >> ~/.bashrc

step 3:
sudo reboot
