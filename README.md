# volumioMycroft
Integration of a mycroft core  in the volumio os 

1. Downloaded the volumio image from http://updates.volumio.org/pi/volumio/2.513/volumio-2.513-2018-12-07-pi.img.zip
2. Setup wifi as documented in https://volumio.github.io/docs/User_Manual/Quick_Start_Guide.html
3. Enable ssh
4. update the package list <<sudo apt-get update>>
5. install cmake << sudo apt-get install cmake>> 
5. clone the mycroft code as suggested in https://github.com/MycroftAI/mycroft-core, cloning the master branch with git clone --depth=1 --branch=master https://github.com/MycroftAI/mycroft-core.git
6. following instruction to install mycroft (runnin dev-setup.sh)
7. type export LC_ALL=C
8. just create the file /etc/asound.conf
  
