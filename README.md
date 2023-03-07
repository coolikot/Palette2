# Palette2

<pre>
Setting up the Palette 2
I got for free with a local market place deal
I had to replace the IO board ordered directly from mosaic manufacturing

now i'm testing it out with an RPI 4b 4GB ram
setting up octoprint : https://www.youtube.com/watch?v=mnN4HVmjafs
fixing the canvas and palette plugin issue :  https://support.mosaicmfg.com/Answers/View/1218/No+Canvas+tab+in+Canvas+Hub+website.

1) Uninstall Canvas and Palette plugins from Octoprint.
2) SSH into the RPi, if you are using Windows you can use PuTTY. You can also use an IP scanner to get the IP address from the RPi, using the IP address as the hostname to connect to. Once you have the IP address, copy and paste it into PuTTY as the host to connect to.
3) Unless you have already configured your RPi login, the default id and password to access the Raspberry Pi is:

pi
raspberry

If the Pi has not been reset, the password is your serial number in the format xxxx-ch in lowercase

4) Once the connection is established, please enter the following three commands separately.
a. sudo apt-get update
b. curl -L https://get.octoprint.org/py3/upgrade.py --output upgrade.py
c. python3 upgrade.py
5) Once the Python update is complete, please reboot the RPi.
Afterwards, reconnect to Octoprint and re-install both the Palette and Canvas plugins.

https://gitlab.com/mosaic-mfg/canvas-plugin
![image](https://user-images.githubusercontent.com/85612975/223461734-877247cf-57b6-4070-b7f1-cfd06a316757.png)

![image](https://user-images.githubusercontent.com/85612975/223461833-e56ecc6f-2559-44bd-b4d5-14d1b8c79f47.png)


https://gitlab.com/mosaic-mfg/canvas-plugin/-/issues/5

use this command if already using python3 

"https://gitlab.com/mosaic-mfg/canvas-plugin/-/issues/5"

then refresh browser see if canvas plugin will show up.

![image](https://user-images.githubusercontent.com/85612975/223468555-e322504b-c460-4b0b-9d01-a7e56182f02e.png)

install palette 2 plugins. and put in cables. 
Canvas Set up done!
</pre>
