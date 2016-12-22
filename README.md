# art-fort-toolkit
Boilerplate for creating alternative art spaces online, in 3D and VR

![alt text](https://github.com/321C4/art-fort-toolkit/raw/master/assets/img/art-fort-screenshot.png "Art Forts")

### Basic Nav
The toolkit site can be veiwed on a regular desktop browser, as well as in Google Cardboard, Oculus Rift, or HTC Vive.
0. Desktop viewing: Use the W A S D keys to move around, and click and drag with the mouse to turn/look.
0. Cardboard: go to https://321c4.github.io/art-fort-toolkit/ on your phone. Tap the VR button (looks like a mask). When the screen view splits, put your phone in the Cardboard viewer.
0. Rift and Vive: You'll need a special experimental browser. Here is how to get one: https://webvr.info/

### Make Your Own!
Fork or download yourself a clone to hack on! You can download the complete toolkit site as a zip, and use without a Github account, if desired.
The toolkit is a simple site, with an index (home page) and a few example-gallery pages. I hope you can use these as a jumping off point, for creating waaaaay more interesting stuff. I'll keep adding to it, and will take requests for types of boilerplate, as well.

### A Local Server for Working on Your Project
Browser Sync server has been suuuper useful for me, so here is how you can use it, too! 

To install the server:
0. Install node.js https://nodejs.org/en/ (this will also install npm, which is used to install the server.)
0. Open the command line -- Terminal on Mac, Command Prompt on Windows -- and type:
```
npm install browser-sync
```
Hit 'enter', and it should install globally.

To run the server:
0. Open the command line -- Terminal on Mac, Command Prompt on Windows -- and move into the directory that has the index.html of the site:
```
cd complete/path/to/your/directory
```
0. Hit enter. Now start the server, with flags to watch for html files and stylesheets:
```
browser-sync start --server --files "*.html, stylesheets/*.css"
```
0. When you hit enter, the server starts up, and automatically starts up your default browser, displaying your index.html file, at the URL http://localhost:3000/index.html
0. To view local site on your phone using wifi, look at the command line: it should now be displaying a local address, and an external address, which looks like the ip address and port number.. Type the "external" address into your phone browser, and you will go to the index of the site. Pretty neat. Makes it quick to view on Google cardboard!

### A-Frame VR Docs:
There are a lot of useful code-snippets in here, as well as info on all different kinds of things you can do with the framework.

https://aframe.io/docs/0.4.0/introduction/

This stuff is still super new and experimental, and getting better all the time.
If you get stuck or have questions, or just want to nerd out about art and webVR together, give me a shout!
skyislandsvr@gmail.com

Happy Hacking :)
