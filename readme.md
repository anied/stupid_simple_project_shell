#Stupid Simple: Project Shell
This repo is a quick and easy project shell to rapidly get an environment up and running for development.  This is probably not a long-term environment solution for your project, but to quickly get up and running this will do the job quite nicely.  Leverage the [http-server](https://github.com/indexzero/http-server) node module.  To use this project shell you must have [Node](https://nodejs.org/) and [NPM](https://www.npmjs.com/) installed.

## How To Use Stupid Simple
+ Copy the contents of this repo to the folder where you intend to host your project.
+ Run `npm install` to install http-server.
+ Run `npm start`
+ Navigate to `localhost:8080` -- you should see "Hello world!"

You now have a webserver up and running for your project.  The webserver is pointing at the `/src` directory.  SO- now its time to make it your own.  Update relevant information in package.json (but don't delete the current start script nor devDependencies unless you're sure you know what you're doing).  Delete or replace this readme.  And clear out index.html and start building your project in there.

##License
There's really nothing particularly original in this repo-- it's just a project shell.  Grab it and use it as you wish.  If you appreciate having this project shell available, consider starring it in Github.
