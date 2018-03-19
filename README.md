
# expressworks

Learn Express.js from the author of one of the best books on Express.js—Pro Express.js—workshop to teach you basics of Express.js.

Installation (Recommended)

Recommended global installation:
```
$ npm install -g expressworks
$ expressworks
```
If you see errors, try:
```
$ sudo npm install -g expressworks
$ expressworks
```
Local Installation (Advanced)

Run & install locally:
```
$ mkdir node_modules
$ npm install expressworks
$ cd node_modules/expressworks
$ node expressworks
```
Optional step that gives you the global command (expressworks) in the Terminal/command prompt:
```
$ npm link
$ expressworks
```
Usage

`$ expressworks`

Note: ExpressWorks depends on a local copy of Express being available in your project folder. To do the exercises, make sure to install the Express.js with
```
$ npm init
$ npm install express@4.11.2
```
See Offline Setup for more required dependencies.

ExpressWorks understands these commands:

Usage

  expressworks
    Show a menu to interactively select a workshop.
  expressworks list
    Show a newline-separated list of all the workshops.
  expressworks select NAME
    Select a workshop.
  expressworks current
    Show the currently selected workshop.
  expressworks run program.js
    Run your program against the selected input.
  expressworks verify program.js
    Verify your program against the expected output.

Offline Setup

If you would like to setup all node packages beforehand, you can complete this workshop offline. Here are all the modules to install with exact versions that this workshop supports:
```
$ npm install express@4.11.2
$ npm install pug@2.0.0-beta6
$ npm install body-parser@1.12.0
$ npm install stylus@0.50.0
```
Note: You need to have node_modules or packagen.json in your project folder before installing dependencies. Run $ mkdir node_modules or $ npm init to create one of them.
Reset

If you want to reset the list of completed tasks, clean the ~/.config/expressworks/completed.json file.