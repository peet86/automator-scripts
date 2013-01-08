peet86's automator-scripts
=================
This repo is a small collection of my everyday use Automator (OSX) scripts/apps. 
Most of the scripts are very simple apple/bash snipet in an Automator generated app. 
Feel free to use or fork them!


Apache Restart 
---------------
Restart your OSX apache daemon with just one click!
The apachectl command require admin privileges, the app will ask for your password.


SSHD - mount your remote hard drive (through ssh) 
--------------------------------------------------
Mount your server's file system or a remote path like an USB drive!
Requirements: ssl public key based login to the remote machine


SSH 
----
Very simple Automator app to log in remote machines via ssh. 
Requirements: ssl public key based login to the remote machine
 


INSTALL & RUN:
===========
Every script is a ready to run app package, but you should set some parameters (ex: your server address, etc.) in the source code. 
Don't worry, you can simply edit the source with your Automator application:

- 1. Move the downloaded app to the Applications folder.
- 2. Run Applications / Automator
- 3. File > Open - select the app
- 4. Modify parameters
- 5. File > Save 
- 6. Run.


License: 
========
All of my scripts in this repo published under Apache License 2.0 (Apache-2.0) 