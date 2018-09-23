# Empty React Bootstrap project

### It's empty React + Bootstrap app project that include all settings to start coding your project;
1) Just copy it to your future project folder, 
2) Type in console at your project folder: <code>npm install</code>
3) Take a look at "scripts" section at "package.json"

+ To install babel use: <code>npm install -g babel-cli@6.24.1</code>
+ To install live-server use: <code>npm install -g live-server</code>

> All will be installed globally so you will not have a need to do it again

Is everything ready? :) 
Let's move on

### A little overview of "Scripts" section in "package.json":
> Notice: To run a script, type in console: <code>npm run scriptName</code>
+ "build": it creates  <code>bundle.js</code> from your original JS (It's not watching for your changes, you need every time as you got changes run this script, it's not convinient, so I don't use Browserify, but do Watchify instead, until I get accustomed to Webpack)
+ "live": it starts live-server and watching "public" folder. 
+ "wf": Here it's where Watchify running (it creates file <code>bundle.js</code>, watching for it and doing all changes to it automatically) (Use it as you need apply some Node.js modules for using with HTML.
+ "bab": This guy converts all your React + JavaScript XML and ES6 to understandable ES5 code.  
