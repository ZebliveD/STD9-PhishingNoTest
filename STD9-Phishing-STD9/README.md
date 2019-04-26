STD9-Phishing - http server for phishing
=================================

[STD9]

DISCLAIMER
==========

Usage of STD9-Phising for attacking targets without prior mutual consent is illegal.
STD9-Phishing developer not responsible to any damage caused by STD9-Phishing.

About
=====

HTTP server for phishing in python.
STD9-Phishing has support for most of the (bigest) websites.

Usually you will want run STD9-Phishing with DNS spoof attack. (see dsniff, ettercap).

STD9-Phishing will do the following steps:
------------------------------------

1. Create fake html page.
2. Wait for clients
3. Grab the data (POST).
4. Try to login the client to the original page :smiley:

Requirements
============

* Python <= 2.7.
* Python BeautifulSoup 4

Install BeautifulSoup
---------------------

* Archlinux        - sudo pacman -S python2-beautifulsoup4
* Ubuntu/Linuxmint - sudo apt-get install python-bs4
* For another OS:  - sudo pip install beautifulsoup4

Platforms
-----------

* Linux (any)
* Mac (Not tested)
* Windows (Not tested)

Usage
======

Just type `help`

Run server:
-----------

* For port 80 you need to run STD9-Phishingas root!

* Host to clone (Ex: www.social-networks.local)
> set url http://localhost

* "<code><"form action = "TAKE THIS URL">"</code>(View the site source and take the URL)
> set action_url http://localhost/sendlogin 

* The port STD9-Phishing server will listen
> set port 2020

* Start the server
> run

The settings will be saved for the next time you run STD9-Phishing.py.

Get STD9-Phishing
=============
                git clone git://github.com/ZebliveD/STD9-Phishing-STD9
  
ZebliveD <zdark426@gmail.com>.


