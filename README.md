# **YT-Player-OBS: YouTube Live Browser Source for OBS**

YouTube Live Browser Source for OBS for streaming YouTube Live stream to other platforms.

Based on https://developers.google.com/youtube/player_parameters#Embedding_a_Player

Updated by TheNolanK on 24 August 2022

## **Adding to OBS**
To add in OBS, add Browser Source

Create New and Name the source YTPLAYER

Check the 'Local File' Box

Select file 'YT-Player-OBS.html'

Set Width to OBS Canvas Width

Set Height to OBS Canvas Height

Leave Default Custom CSS

Check the 'Shutdown source when not visible' Box

Check the 'Refresh browser when scene becomes active' Box

![OBS Browser Setup](https://i.imgur.com/h1RFSuZ.png)

## **Customizing Your Parameters**

To customize this code for your stream, make sure these three parameters reflect your setup: Width, Height, and Video ID

### **WIDTH**
Set width above to width of OBS Canvas

### **HEIGHT**
Set height above to height of OBS Canvas

**Can be found in OBS -> File -> Settings -> Video**

![OBS Canvas](https://i.imgur.com/w2GFHDm.png)

### **VIDEO ID**
Replace 'BKFzJJbz_m0' with the video ID of your YT stream

Can be found either as https://www.youtube.com/watch?v=YOUR_CODE_HERE or as https://youtu.be/YOUR_CODE_HERE

Note: Video ID should not have any ? or & or = Symbols

## **NOTES**

After making the changes, save updated file. Make sure the saved file ends in **.html**  and *not .txt, .rtf, or .docx.*
