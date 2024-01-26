# Incident_Chatbot
Packages needed to be installed:

pip install slackclient

pip install flask

pip install slackeventsapi

pip install python-dotenv

pip install pathlib

pip install requests

pip install beautifulsoup4

Setting up local test server

I use an application called ngrok which is free and easy to use. Download ngrok here: https://ngrok.com/download Extract all the contents out of the zipped folder and double click the ngrok application file to open it. To run a web server on port 5000, type "ngrok http 5000"

NOTE: Make sure to first run the ngrok server and then run the python script: python bot.py

Everytime you create a new web server, ngrok's link changes. You will need to paste the new link in the Event Subscriptions section. Make sure Enable Events is on as well as the "Subscribe to bot events" section has message.channels as an event. On top of this, you will need to paste the new ngrok link for the slash command section otherwise you will get the error of "dispatch failed".
[UTOBuildingIncidentBot-master.zip](https://github.com/aaronbarought/Incident_Chatbot/files/14069633/UTOBuildingIncidentBot-master.zip)
