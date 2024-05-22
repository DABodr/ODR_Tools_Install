* Auto-install script of ODR tools for RaspberryPi ARM with Buster, Jessie & Stretch distribution and Debian systems.


 More infos on www.opendigitalradio.org for ODR tools development.               
 Configuration ready for transmit with an EasyDABv2 : https://tipok.org.ua/node/46

  * Install:

- sudo adduser (username) sudo 
- git clone https://github.com/DABodr/ODR_Tools_Install.git
- cd ODR_Tools_Install
- chmod +x ./Install.sh
- ./Install.sh
It will make a "dab" directory in /home/$USER/ , install all dependency for odr-mmbtools and all tools for run simply a DAB+ multiplex:
   *   ODR-DabMux (DAB/DAB+ multiplexer) 
   *   ODR-AudioEnc (DAB/DAB+ audio encoder)
   *   ODR-PadEnc ( MOT slideshows and DLS encoder)
   *   DABlin ( DAB/DAB+ player for local and remote multiplex)
   *   Auxiliary scripts
   *   The FDK-AAC v2 library with DAB+ patch
   *   Supervisor (automatisation of all tools)
