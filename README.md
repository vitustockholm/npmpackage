Deployd to npmjs.com server

https://www.npmjs.com/package/npmgamepackage

///////////////////////////////////////////////

Own Command Line Interface (CLI)
Quiz type CLI game:

- Enter Player name

\*can handle colors, animation, and user input with ease.
\*promises etc

For making copy of script follow:

1. Create new project default package.json file:
   npm init -y

2. Change in package.json:
   "type": "module",

3. Install dependencies
   npm install chalk
   chalk-animation
   figlet
   gradient-string
   inquirer
   nanospinner

4. Add in package.json

"bin": "./index.js",

5. npm login
   \*must have account on npm web

6. npm publish
