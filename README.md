# liri-node-app

get keys:
//omdb api key
OMDb API: http://www.omdbapi.com/?i=tt3896198&apikey=---------

// Spotify
Client ID -------------------------
Client Secret ------------------------------

//twitter
Consumer Key (API Key)	-----------------------------
Consumer Secret (API Secret)	------------------------------
Access Token	---------------------------
Access Token Secret	

var keys = require("./keys.js");
var request = require('request');
var Twitter = require('twitter');
var Spotify = require('node-spotify-api');
var fs = require('fs');
var client = new Twitter(keys.twitterKeys);
var input = process.argv;
var action = input[2];
var inputs = input[3];

code 'switch', 'case' for spotify, twitter, omdb and 'do what it says'

function twitter(inputs) 
function spotify(inputs) 
function omdb(inputs) 

fs.readFile
'if - else' statements for different user input requests