# LiveStramingCamera
DIY live streaming camera using raspberry pi, opencv, flask and remote.it

Essential libs<br/>

echo Y |sudo apt-get install libopenjp2-7-dev<br/>
echo Y | sudo apt-get install libhdf5-dev<br/>
echo Y |sudo apt-get install libqtgui4 libqtwebkit4 libqt4-test<br/>
echo Y | sudo apt-get install libatlas-base-dev<br/>
echo Y | sudo apt-get install libjasper-dev<br/>
echo Y | sudo apt-get install python3-pip<br/>
echo Y | sudo apt-get install python3-h5py<br/>
echo Y | sudo apt-get install python3-opencv<br/>
echo Y | sudo pip3 install flask<br/><br/>
sudo apt install remoteit<br/>



Wfi Settings for Raspbian OS</br></br>

File Name: wpa+supplicant.conf<br/>
Contents:<br/>
country=CH<br/>
 ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev<br/>
 network={<br/>
      ssid="YOUR_NETWORK_NAME"<br/>
      psk="YOUR_PASSWORD"<br/>
      key_mgmt=WPA-PSK<br/>
 }
