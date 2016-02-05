# musicsync

This python script allows you to synchrinize a directory with an iTunes playlist
For example, copy it in a folder on your phone sd card (needs Mass Storage mode) and execute it. It will read the iTunes xml file and will synchronize the playlist in the folder.

To make it work, ther is  things to change in the script:
1. setup the xml fil path
  example : xmlFile = "C:\\Users\\User\\Music\\iTunes\\iTunes Music Library.xml"
2. setup the name of the playlist to synchronize:
  example : playlistName = "Phone"
  
  
Limitation:
-There is no interface at all, you need to edit the script to make it work (at least once)
-it doesn't work when the phone is not set in mass storage mode (MTP mode doesn't work)

