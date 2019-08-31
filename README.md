# PhaserMultiplayerLessonPart1
PhaserJS Multiplayer Lesson Part 1

// TUTORIAL PART I: https://gamedevacademy.org/create-a-basic-multiplayer-game-in-phaser-3-with-socket-io-part-1/

// Check To Make Sure Node.JS is Installed
$ node --version

// If not installed, download here: https://nodejs.org/en/

// Navigate to your project directory, and install ExpressJS
$ cd ~/
$ cd Desktop
$ mkdir PhaserMultiplayer
$ cd PhaserMultiplayer
$ npm install --save express

// Download & Install Ngrok: https://ngrok.com
// REFERENCE: https://dashboard.ngrok.com/get-started
1) Download ngrok
2) Unzip to install
3) Connect your account $ ./ngrok authtoken cheCKnGrOKforYOURauthToKeNWHIchGOEsHere
4) Fire it up $ ./ngrok http 8081

// Add index.html file to PhaserMultiplayer Directory

// Create a js subdirectory in the PhaserMultiplayer Directory

// Add game.js to the js sub directory

// Create server.js file in PhaserMultiplayer Directory

// Run node.js server
$ cd ~/
$ cd Desktop/PhaserMultiplayer
$ node server.js

// Run ngrok tunnel from another terminal
$ cd ~/
$ ./ngrok http 8081

// Install socket.io
$ npm install --save socket.io

// Add socket.io code to server.js and game.js
