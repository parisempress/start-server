start-server
============

II have started to work on the server.... the main goal of this project is to web api...
you can create a Rest-api skeleton  and extend it later  with your own code.



Start sever
// import
var Skeleton =require ("webapi-skeleton");
// setup
var app = skeleton.bootApp({
"config": _ dirname + "/../config",
"controls" : _dirname + "/../impl/controls",
"mongodb" : "mongodb://localhost/restApp",
"schema":_ dirname + "/../config/database"
}, tables );
// start
app.run (function(app){
// callback after initialization});
