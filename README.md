Torsangsuk2 on EasyRTC Server 
======================

Files and Folders:
------------------

 - package.json - Provides project information allowing npm to find and install required modules.
 - \torsangsuk2\server.js - Torsangsuk2 Server code.
 - \torsangsuk2\node_modules\easyrtc\demos\myapp -  Torsangsuk2 codes are here

 
Installing Required Modules:
----------------------------

 - Type `npm install` in console.
 - This will read the package.json file to find and install the required modules including EasyRTC, Express, and Socket.io.
 - Required modules will go into a new 'node_modules' subfolder


Running the Server:
-------------------

 - Type `node server.js` in console (such as Linux Terminal and Git Bash).


Viewing the examples:
---------------------

 - In your WebRTC enabled browser, visit your server address including the port. By default port 8080 is used.
 - http://localhost:8080/demos/myapp/videochat.html
