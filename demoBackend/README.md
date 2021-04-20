# Backend Brief Introduction

Welcome to Jedi team's backend demo

This demo's technology involves Bootstrap, Highcharts, MySQL and Node.js Environment. This backend project presents how to connect website and local database via Node.js service and how to make data into charts (Data Visualisation).

Introduction

```bash
- /pubilc
    - bower.json 
    - index.html # a simple frontend page includes components such as HighCharts & JQuery which can call the service to make data visualising in charts
- server.js # Generate connection service that query table from MySQL Database
- package.json
```

# Demo Start Tutorial

Requirement Environment:
    - MySQL > 8.0
    - node > 11.0
    - bower 1.8 / npm > 6.7

1. Using `cd` to locate at project folder
2. Input `npm install` in project root path, then you will see `node_modules` and `package-lock.json`
3. Input `bower install` in the demoBackend/public folder, then you will see `bower_components`
4. Create a new schema(database) called `casa-web` and insert table by importing the `accidents_london.json` file into this new created schema
5. Input `node server.js` to excute this demo
1. Connect to (http://localhost:3000/index.html) to show the graph.
