NagliteTwit
========

Nagios status monitor for a NOC using the popular twitter bootstrap.

Inspired by Naglite3 (https://github.com/saz/Naglite3) 
Written by Steffen Zieger <me@saz.sh>.
Licensed under the GPL.

Modified by me to improve the look of a few things and remove a few things
The repo is a mess, it is my first one, please feel free to clone and modify to fit your needs

I cannot be resonsible for the missuse of these files, if there is a problem shoot me an email at mylivingweb@gmail.com

Requirements
------------

NagliteTwit has only been tested with NagiosXI and CentOS 6.3, but it should also work with Nagios3.

- Web server of your choice with PHP support
- PHP 5.2 or newer
- git

NagliteTwit must be installed on the same host where Nagios is running, as it
needs to read status.dat from Nagios.

Installation
------------

1. Switch to a directory accessible through your web server (e.g. /var/www/html).
2. git clone https://github.com/mylivingweb/NagliteTwit.git
3. Go to line 143 and change LOCALHOST to your server
4. Open a browser and point it to your NagliteTwit installation.

