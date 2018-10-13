# Playground
This is a web application built to test basics of react.js + javascript

# Prerequisites

## babel-cli
To compile this application it is required to use babel-cli, install it  running the following command:

`npm install -g babel-cli`

Add `@6.24.1` to set a specific babel-cli version

## live-server
To run this application you can use live-server, install it running the following command:

`npm install -g live-server`

Add `@0.24.5` to set a specific live-server version

# Build 
To build the project use the following command:

`babel src/playground/*.js --out-file=public/scripts/app.js --presets=env,react` 

Add the `--watch` flag to automatically build the project when new changes are made

# Run
To run with live-server use te following command:

`live-server public`
