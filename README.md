# Automate_spotify
This python program automates your spotify playlist using the videos you liked on Youtube


## Technologies
* [Youtube Data API v3]
* [Spotify Web API]
* [Requests Library v 2.22.0]
* [Youtube_dl v 2020.01.24]

## LocalSetup
1) Install All Dependencies   
`pip3 install -r requirements.txt`

2) Collect You Spotify User ID and Oauth Token From Spotfiy and add it to secrets.py file
    * To Collect your User ID, Log into Spotify then go here: [Account Overview] and its your **Username**
    * To Collect your Oauth Token, Visit this url here: [Get Oauth] and click the **Get Token** button

3) Enable Oauth For Youtube and download the client_secrets.json   
    * Ok this part is tricky but its worth it! Just follow the guide here [Set Up Youtube Oauth] ! 
    If you are having issues check this out [Oauth Setup 2] and this one too [Oauth Setup 3] 

4) Run the File  
`python3 create_playlist.py`   
    * you'll immediately see `Please visit this URL to authorize this application: <some long url>`
    * click on it and log into your Google Account to collect the `authorization code`

The above work is an interpretation of a project from "The Come Up"
