# RTKLIB Touchscreen GUI

RTKLIB GUI (Graphic User Interface) for Raspberry Pi with touchscreen made with Qt4 by the ENSG students 

Take a look to the wiki pages for installation instructions and user manual :  https://github.com/Francklin2/RTKLIB_Touchscreen_GUI/wiki

# Material : To build this project you will need :

- Raspberry pi 2 and a 8gb SD
 
![Github Logo](http://static.generation-robots.com/4982-large_default/raspberry-pi-2-modele-b-avec-carte-sd-8go-noobs.jpg)

- 5 inch HDMI touchscreen like this one
https://www.amazon.fr/Waveshare-Raspberry-Resistive-Interface-Rapsberry/dp/B00TIA0PMQ

![Github Logo](https://images-na.ssl-images-amazon.com/images/I/51z9l-kvd6L._SX466_.jpg)

- Talysman antenna 
http://www.digikey.fr/product-detail/fr/0/1526-1016-ND
![Github Logo](http://media.digikey.com/Photos/Tallysman%20Wireless/33-3400-01-01.jpg)

- TNC/SMA adapter like this
http://www.ebay.fr/itm/370949049924?_trksid=p2060353.m2749.l2649&ssPageName=STRK%3AMEBIDX%3AIT

![Github Logo](http://i.ebayimg.com/00/s/NTAwWDUwMA==/z/5AQAAOSw0vBUjxfN/$_12.JPG)

- GNSS Ublox M8T, you can found cheap one at csgshop.com
http://www.csgshop.com/product.php?id_product=205

![Github Logo](http://www.csgshop.com/img/p/205-470-thickbox.jpg)

- Standard rectangular on/off power switch
http://www.ebay.fr/itm/5Pcs-2-Pin-Snap-in-On-Off-Position-Snap-Boat-Rocker-Switch-12V-110V-250V-K0TG-/311562995499?hash=item488a9a072b:g:zbAAAOSwxp9W39wh

![Github Logo](http://i.ebayimg.com/00/s/NjAwWDYwMA==/z/zbAAAOSwxp9W39wh/$_12.JPG)

- Régulator Ubec 5V , you can found them in any RC-model shop
http://www.ebay.fr/itm/5V-3A-Mini-UBEC-BEC-Converter-Step-Down-Module-For-RC-Plane-FPV-DIY-Aircraft-Fly-/131676464873?hash=item1ea88766e9:g:zmQAAOSwvUlWsgG4 

![Github Logo](http://i.ebayimg.com/00/s/MTAwMVgxMDAx/z/zmQAAOSwvUlWsgG4/$_57.JPG)

- Battery Adapter Mounting Plate for NP-F970
http://www.ebay.fr/itm/Battery-Adapter-Mounting-Plate-fr-NP-F970-F750-F550-Sony-Battery-970-DSLR-Rig-/172049210887?hash=item280eee9e07

![Github Logo](http://i.ebayimg.com/00/s/MTAwMFgxMDAw/z/-vcAAOxydB1SiZTm/$_57.JPG)

- Battery Sony NP-F970 or a compatible one ( you can find many cheap clones)
http://www.ebay.fr/itm/6600mAh-NP-F960-NP-F970-Batteries-pour-NP-F930-F330-F550-F750-F770-SONY-Appareil-/281720172938?hash=item4197d4b18a:g:GN4AAOSwBahVeQMW

![Github Logo](http://i.ebayimg.com/00/s/MTAwMFgxMDAw/z/GN4AAOSwBahVeQMW/$_57.JPG)

- Charger for battery NP-F Sony 
http://www.ebay.fr/itm/Dual-Channel-Battery-Charger-For-SONY-NP-F970-F750-F960-FM50-FM500H-FM55H-QM91D-/371008913548?hash=item5661dac08c:g:9UUAAOxyLm9TAttp

![Github Logo](http://i.ebayimg.com/00/s/MTAwMFgxMDAw/z/9UUAAOxyLm9TAttp/$_57.JPG)

- mini USB angled for wiring the GNSS
http://www.ebay.fr/itm/Court-20cm-Angle-Droit-USB-A-a-90-degres-Angle-Droit-Mini-B-USB-Data-Cable-Cable-/221683667935?hash=item339d6053df:g:dDoAAOSwPhdU1PcB

![Github Logo](http://i.ebayimg.com/00/s/ODAwWDgwMA==/z/dDoAAOSwPhdU1PcB/$_57.JPG)

 - Serial RF link, 2 units needed to link a rover too a base like a Xbeepro or a cheaper 3DR télémetry module(Half duplex only !)
 https://www.sparkfun.com/products/10419
and
http://www.ebay.fr/itm/3DRobotics-Radio-3DR-Kit-Telemetry-433Mhz-Module-for-APM-APM2-5-2-6-Pixhawk-PX4-/221852845151?hash=item33a775c45f:g:0YgAAOSwgQ9V0Un~

![Github Logo](https://cdn.sparkfun.com//assets/parts/4/8/9/3/10419-01.jpg)

![Github Logo](http://i.ebayimg.com/00/s/MTAwMFgxMDAx/z/0YgAAOSwgQ9V0Un~/$_57.JPG)

- Wifi dongle to for internet Ntrip GNSS correction
-http://www.ebay.fr/itm/Wireless-USB-Adapter-LAN-Wifi-Dongle-for-Raspberry-Pi-802-11-b-g-n-150Mbps-PK-/311440828311?hash=item488351e797:g:UJIAAOSwWnFV7mJy

![Github Logo](http://i.ebayimg.com/00/s/MTAwMVgxMDAx/z/UJIAAOSwWnFV7mJy/$_57.JPG)

- A 1/4 to 3/8 inch screw adapter to mount the RTKBASE on any stands
http://www.ebay.fr/itm/2PCS-3-8-to-1-4-inch-convert-screw-thread-adapter-tripod-ball-head-/231677594811?hash=item35f10f8cbb:g:qYoAAOSwqv9V6u21

![Github Logo](http://i.ebayimg.com/00/s/NTA2WDYxOA==/z/qYoAAOSwqv9V6u21/$_12.JPG)


# Installation
To install system on a raspberry pi 2 with the touchscreen you can download a raspian image with all the touchscreen drivers, Qt4 and all compilation dependencies preinstalled here :

https://drive.google.com/file/d/0B5xmVAi4jATOcXE3a3BWS0VDUUk/view?usp=sharing

It was based on this original image with only the library for the touchscreen: https://drive.google.com/file/d/0B2SuLGFxizpVMzRtODVkN0tZVjA/view?usp=sharing



You can also download this Pré-installed image of RTKbase, this contain a master version (june 2016) with autoload and custom splash screen

https://drive.google.com/open?id=0B5xmVAi4jATOcEQ1TWxaOXprMk0


- Copy this image on a SD card, you can use Rufus for that : https://rufus.akeo.ie/
- Insert the SD card in your Raspberry Pi and start it.
- Open the terminal and clone the repository:
```
git clone https://github.com/Francklin2/RTKLIB_Touchscreen_GUI
```
- Go to the RTKBASE directory: 
```
cd  RTKLIB_Touchscreen_GUI/RTKBASE/
```
- Run the script to compil:
```
./build_rtkbase.sh
```
- Launch RTKBASE:
```
./RTKBASE
```

# Autostart RTKBASE at boot :                                                                          

Very simple but many method to do it :

1) Add software to rc.local 
Run : 

```
sed -i -e '$i \cd /home/pi/RTKLIB_Touchscreen_GUI/RTKBASE/ && RTKBASE\n' rc.local
```

2) Use system root LXDE autostart : 
Run : 

```
sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
```

Add this :

```
@/home/pi/RTKLIB_Touchscreen_GUI/RTKBASE/
@RTKBASE
```

3) Use user LXDE autostart : 
Run : 

```
nano ~/.config/lxsession/LXDE/autostart
```

Add this :

```
@/home/pi/RTKLIB_Touchscreen_GUI/RTKBASE/
@RTKBASE
```

4) Add desktop entry to user config : 
Run : 

```
nano ~/.config/autostart/rtkbase
```

Copy paste entry below :

```
[Desktop Entry]
Name=RTKBASE
Type=Application
Comment=RTKLIB Touchscreen : graphic interface to use GNSS.
Exec=/home/pi/RTKLIB_Touchscreen_GUI/RTKBASE/RTKBASE
Make it executable : 
chmod +x ~/.config/autostart/rtkbase
```

Best way for me is option 4 because I do not use LXDE

Source : http://www.raspberrypi-spy.co.uk/2014/05/how-to-autostart-apps-in-rasbian-lxde-desktop/ and kikislater


# What will you get :

![Github Logo](https://raw.githubusercontent.com/Francklin2/RTKLIB_Touchscreen_GUI/master/3D%20Printing/Francklin.jpg)


![Github Logo](https://github.com/Francklin2/RTKLIB_Touchscreen_GUI/blob/master/3D%20Printing/RTK_DW.JPG)

Vidéo of beta build :

[RTKlib Touchscreen preview](http://www.youtube.com/watch?v=-d_Dm6mLMMQ)  

[RTKBASE video Preview 2](http://www.youtube.com/edit?video_id=iNINaH6aKpc)

# How to process data : 

Go to Wiki

# What precision and accuracy will I get ?

Work in progress ... Stay tuned !

You can watch some information here : 

http://marcotte-ag.no-ip.org:8080/geomatic/index.html

http://www.afhy.fr/images/pdf/Rapports/UV54_2016/poster_gnss_PPP_GTX.pdf

http://www.gps.gov/cgsic/meetings/2012/lyle.pdf
