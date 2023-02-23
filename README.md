# Excel-music-player

![alt text](https://github.com/Shadox-0495/excel-music-player/blob/master/cover.png?raw=true)
A scheduled music player made in Microsoft Excel. The player is programmed to play songs assigned to the playlist but only during specific time slots designated in the playlist configuration.

## Explanation
Why? you may ask, well the short answer is because you can, the long answer is there was a need to play specific gender of music throughout the day, and since there was no access to the visual studio I improvise something in Excel and this was the result.<br />
Now, this was made in Microsoft Office 2019, so I can't promise that it works on other versions of Microsoft Office, use it at your own risk.

# Use
Click the [Open Player] button to show the main dialog along with the other actions.

## Create playlist
click [Create Playlist] -> insert the playlist name along with it's starting and ending time -> click [Save] button

## Add songs
It's required to create a plyalist before adding the songs.<br />
click [Add Songs] -> select a playlist from the combobox -> click [Browse Files] button -> select all the audio files that you want to add to the playlist -> click [OK button] -> close the add songs dialog.

## Remove plylist
Note: This will remove the playlist an all it's songs.<br />
click [Remove playlist] -> select a playlist from the combobox -> click [Remove playlist] button -> confirm removal ->  close the remove playlist dialog.

## Sheets
Player -> Contains the show player button.<br />
Playlist -> Contains all created playlists.<br />
Songs -> Contains all songs added to the playlist<br />
<br />

# Warning
You can modify the data in either sheet but don't remove the filters in the Songs sheet, it can cause issue with the code.
