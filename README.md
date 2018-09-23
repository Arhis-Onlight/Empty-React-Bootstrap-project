# Empty React Bootstrap project

Here we go...
It's empty React + Bootstrap app project that include all settings to start coding your project;
1) Just copy it to your future project folder, 
2) type in console: npm install
3) take a look at "scripts" section at "package.json"

Is everything ready? :) 
Let's move on

A little overview of "Scripts" section:
Notice: To run a script type in console: npm run scriptName
1) "build": create a bundle.js from your original JS (It's not watching for your changes, you need every time as you got changes run this script, it's not convinient, so I don't use Browserify, but do Watchify instead, untill I got accustumed to Webpack)
2) "live": it starts a live-server from the folder "public". (You need to install it in advance with command: npm install -g live-server)
3) "wf": Here it's where Watchify running (it creates bundle.js, watching for and doing all changes automaticly) (Use it as you need apply some Node.js modules for using with html.
4) "bab": This guy converts all your React JavaScript XML and ES6 to understandable ES5 code.  
