# Brooklyn-College-Alvin-Huang-Web-App-Assignment-3-cisc3140
a barebones api client with NASA’s api. connect with the API and display information from that API

Travis is used - a .travis.yml file for the python app is added in assignment 1 to utilize Travis CI in conjunction with the github repo
This includes instructing the laguage used, the provider, the api key, and the project name under the cloud server.

Requirements.txt- these are the required components that are needed to have it built and deloped to be hosted.
This can be done by doing pip3 freeze to show the required compnents

I tried to deploy my app to a server like heroku

I used this source as reference:
https://mdyzma.github.io/2017/05/20/flask-and-travis-ci/?fbclid=IwAR2oskg4sWRiNQ5S1ir6Mm75k-B30mY9Ov2lcMvAvd2fmxmVgGB2QD4tJRw

Complication: As the travis build was successful, the deployment of the app didn't go well
Soultion: restart heroku

Alternative solution: check travis file, requirements text, or the python files 
