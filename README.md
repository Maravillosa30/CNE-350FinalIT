# Running QBittorent on Raspberry Pi

qBittorent is one of the most popular torrent clients that you can use on the Pi.
It has become known for its relatively stable platform and good feature set that works well on limited-resource devices like the Raspberry Pi.

BitTorrent trackers provide a list of files available for transfer and allow the client to find peer users, known as "seeds", who may transfer the files. 

### Explanation on Project change.

This project was used to replace the Original Project that consisted on using the Raspberry Pi as a Media Center using OSMC (a super lightweight line bistro with a custom version of Kodi installed). 


For the fisrt project, this tutorial [https://www.youtube.com/watch?v=ngGkVd-_LP8&t=301s] was used to download and try to run this software on the Pi.


When the Raspberry was booted, it  showed a rainbow screen. After several congifuration failed, moving on to a new project was the best option. 


## Source Code
The commands to successfuly download and run the qBittorent  on the Raspberry Pi can be found on this link [https://pimylifeup.com/raspberry-pi-qbittorrent/.

 Open the terminal in the Pi and follow this commands to install qBittorent:
 
 1. First and always update and upgrade the raspberry Pi packages before any installation.

    
   ```
      $ sudo apt update
      $ sudo apt full-upgrade
   ```
2. Then install qBittorent for the Deskstop Raspberry Pi. with this commands:
   
   ```
      $ sudo apt install qbittorrent
   ```

3. Follow the instructionsto open qBittorent software  on the Raspberry Pi VNC.
   
   ![alt text](https://github.com/Maravillosa30/CNE-350FinalIT/blob/main/2024-03-20.png)

   Then, the qBittorent will pop open on the screen

   ![alt text](https://github.com/Maravillosa30/CNE-350FinalIT/blob/main/Torrent.png)
  

   Also, enable Web UI through the client software and configure the app to your design.
   

   ![alt text](https://github.com/Maravillosa30/CNE-350FinalIT/blob/main/PreferencesT.png)
   


5.  Lastly, open your favorite Web-browser and enter the Raspberry Pi IP ADDRESS 
   
   





