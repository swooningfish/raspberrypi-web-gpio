raspberrypi-web-gpio
====================

Files to control the GPIO pins of a raspberry pi via a webpage.


Dependences
====================
To run this script you will need a web server and php5, this has been
tested on apache2 running 5.4 but lower versions should work

To install the dependences 

sudo apt-get install apache2 php5 mysql-server


Installation
====================
Run the commands as root or make sure the /var/www directory is owned by 
the user you are logged in as.

e.g. if your username is pi

sudo chown pi:pi /var/www 

Change to the website directory
cd /var/www
Clone the repository
git clone https://github.com/swooingfish/raspberrypi-web-gpio.git


Credits
====================
These files were originally from raspberrypi-gpio - https://code.google.com/p/raspberrypi-gpio/ 
Original install instructions from http://www.instructables.com/id/Web-Control-of-Raspberry-Pi-GPIO/
