Torsangsuk2 (deployed on EasyRTC Server) 
======================

Files and Folders:
------------------

 - package.json - Provides project information allowing npm to find and install required modules.
 - `torsangsuk2/server.js` - Torsangsuk2 Server code (NodeJS).
 - `torsangsuk2/node_modules/easyrtc/demos/myapp` -  Torsangsuk2 codes are here

Installing NodeJS:
----------------------------

 - `https://nodejs.org/download/` 
 - For Linux Servers OS, nodejs-legacy is preferred (Ubuntu Server: `sudo apt-get install nodejs-legacy`)

 
Installing Required Modules:
----------------------------

 - Type `npm install` in console.
 - This will read the package.json file to find and install the required modules including EasyRTC, Express, and Socket.io.
 - Required modules will go into a new 'node_modules' subfolder


Running the Server:
-------------------

 - Type `node server.js` in console (such as Linux Terminal and Git Bash).


Viewing Torsangsuk2 :
---------------------

 - In your WebRTC enabled browser (Google Chrome recommended), visit your server address including the port. By default port `8080` is used.
 - `http://localhost:8080/demos/myapp/videochat.html` is by default
