# LinuxPixelSlate-
Installing linux OS on a Pixel Slate Tablet

##### https://www.howtogeek.com/162120/how-to-install-ubuntu-linux-on-your-chromebook-with-crouton/
##### https://tylervoll.herokuapp.com/ubuntu-linux-on-a-google-pixel-slate/
##### https://warroom.rsmus.com/crouton-chromebooks-as-a-pentesting-platform/

Once you have Crouton downloaded, press Ctrl+Alt+T in Chrome OS to open the crosh terminal.

Type 'shell'  into the terminal and press Enter to enter Linux shell mode. This command only works if Developer Mode is enabled.

Copy the installer to an executable location by running sudo install -Dt /usr/local/bin -m 755 ~/Downloads/crouton
Now that it's executable, run the installer itself: sudo crouton -t xfce

sudo enter-chroot startxfce4

sudo apt install xserver-xorg-core xserver-xorg-video-dummy xserver-xorg-video-intel
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:ubuntu-x-swat/updates
sudo apt update
sudo apt-get dist-upgrade
sudo apt-get install mesa-utils

exit

sudo install -Dt /usr/local/bin -m 755 ~/Downloads/crouton (Makes crouton installer executable)

sudo crouton -u -t kde,touch,keyboard,audio

exit

sudo startkde


to navigate through linux
 Ctrl+Alt+Shift+Back
 Ctrl+Alt+Shift+Forward
