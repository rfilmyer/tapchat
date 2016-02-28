# TapChat: Modern IRC Client

Stay connected with your favorite channels without draining your phone's battery. Scroll back to catch up on what you've missed, and receive push notifications1 when someone mentions or messages you.

 * [Website](http://tapchatapp.com/)
 * [Android App](https://github.com/tapchat/tapchat-android)

Installing
----------

### Install into user directory

    $ npm install
    $ ./bin/tapchat start

### Install system-wide

    $ sudo npm install -g
    $ tapchat start
    
Access the web interface by visiting `https://your_ip_address:port`. (default: 8067) Note that only secure HTTPS is supported. Select the option to save the automatically-generated certificate into your browser after verifying the fingerprint matches.

If you have any problems, you can start tapchat in debug mode:

    $ tapchat start -fv
    
Configuring the Server
------------------

Running tapchat for the first time will prompt you for a port to run on, and generate an SSL certificate. 
This configuration info will be stored in the `.tapchat` folder in your home directory 
(for Macs, it will be in `~/Library/Application Support/Tapchat`).

The setup process will generate a self-signed certificate titled `tapchat.pem`. Feel free to replace this with your own certificate.

Planned Changes for my fork
---------------------------

Haven't worked with coffeescript before, so nothing major:

 * Custom CSS and Themes - Add a dropdown menu for themes (including the ability to add your own CSS)
 * /msg - How the hell else am I supposed to identify to NickServ!?
 * Use a more secure password hashing algorithm (as opposed to one that's been deprecated!)



Authors
-------

 * Original project - [Eric Butler](https://twitter.com/codebutler)
 * Minor improvements - [Roger Filmyer](https://twitter.com/rfilmyer)
 * Pull requests on original project - various

License
-------

    Copyright (C) 2016 Eric Butler

	This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
