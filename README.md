# LiveStreamingCamera
DIY live streaming camera using Raspberry Pi, OpenCV, Flask and remote.it</br>

### Essential Libraries to install<br/>
---------------------------
echo Y | sudo apt-get install libopenjp2-7-dev<br/>
echo Y | sudo apt-get install libhdf5-dev<br/>
echo Y | sudo apt-get install libqtgui4 libqtwebkit4 libqt4-test<br/>
echo Y | sudo apt-get install libatlas-base-dev<br/>
echo Y | sudo apt-get install libjasper-dev<br/>
echo Y | sudo apt-get install python3-pip<br/>
echo Y | sudo apt-get install python3-h5py<br/>
echo Y | sudo apt-get install python3-opencv<br/>
echo Y | sudo pip3 install flask<br/>
sudo apt install remoteit<br/>



### WiFi Settings for Raspbian OS</br>
------------------------------
**File Name:** wpa_supplicant.conf<br/>
**Contents:**<br/>
&nbsp;&nbsp;country="YOUR COUNTRY CODE"<br/>
&nbsp;&nbsp;ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev<br/>
&nbsp;&nbsp;network={<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ssid="YOUR_NETWORK_NAME"<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;psk="YOUR_PASSWORD"<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;key_mgmt=WPA-PSK<br/>
&nbsp;&nbsp;}</br></br>

Known Issues</br>
--------------------
if you face any issue while installing a library like python3-opencv or flask,</br>
then run the "sudo apt-get update --fix-missing" command first.
