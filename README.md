# typescript-node-seed
> TypeScript seed project that focusses on using npm scripts to do all the work

## Features

* TypeScript 1.8, installed locally
* mocha/chai for testing, ts-node for on-the-fly test compilation, nodemon for proper watching / TDD workflow
* no build tool dependencies, only npm scripts

## Starting a new project

* git clone the repository
* remove .git
* npm install
* typings install

## WARNINGs

* I'm just dabbling around with TypeScript and I might be missing obvious stuff
* remember to set **typings** in package.json if you want to properly consume your module from TypeScript

## What's working

* **npm run build** - run tsc
* **npm run build:watch** - run tsc in watch-mode
* **npm run clean** - delete *build* directory
* **npm run lint** - runs tslint
* **npm run repl** - run ts-node to get a REPL
* **npm test** - run mocha on all *.ts files in *test/*
* **npm test:watch** - re-run mocha on all *.ts files in *test/* everytime a file changes 

## TODO

Probably some stuff I'm not seeing right now.

## License

Apache-2.0 © [Mathias Ringhof]()