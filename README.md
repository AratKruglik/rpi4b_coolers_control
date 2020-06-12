# Fan control script for Raspberry Pi

To install and autostart script on RPI boot do next steps:

1. Clone this repo to you home directory on RPI.
2. Edit autoload file: ```sudo nano /etc/rc.local```.
3. Put follow code before ``exit 0``: ```sudo python /home/{YOUR_USERNAME}/cpu_coolers.py &```.
