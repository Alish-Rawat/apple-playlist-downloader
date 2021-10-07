This is the lyrics module of the repository apple-playlist-downloader.
With this code you can download the .lrc file (time synced lyrics) from yours tracks in a apple music playlist.

How to use :

```
npm install
pip3 install -r requirements.txt
```
Set the playlist link at the 'url' variable in the file 'apple_playlist.js'

Get the playlists tracks and copy them into your clipboard :

```
node fetch_playlist.js
```
You'll get an output like this :


<img width="752" alt="Capture d’écran 2021-10-07 à 15 37 06" src="https://user-images.githubusercontent.com/44288655/136427167-f6ca4fd4-beca-41dd-b17f-2db16cadd75a.png">


Then go to the file searcher.py line 68 : 
```
nano +68 searcher.py 
```
Change the line and paste into the '''(here)''' your clipboard.
```
python3 searcher.py
```
Then wait and you will get a result like this :
<img width="1125" alt="Capture d’écran 2021-10-07 à 18 35 28" src="https://user-images.githubusercontent.com/44288655/136427185-aba0dbe3-86db-4d28-ba6f-1520b6364058.png">

All the lyrics are stored in the folder 'lyrics'
Or a message like 'No lyrics found'
