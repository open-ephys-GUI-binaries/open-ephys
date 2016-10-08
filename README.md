# open-ephys

Linux compiled binaries for Open Ephys GUI (https://github.com/open-ephys/plugin-GUI)

Tested on Ubuntu and Linux Mint. If you get it to work on another distro, let us know!

To run the software double-click the "open-ephys" application file.

In order to use the GUI with the Open Ephys acquisition board or one of Intan's eval boards, you'll have to update the permissions for external devices. Open a terminal and navigate to the Open Ephys folder, then type `sudo cp 40-open-ephys.rules /etc/udev/rules.d` and hit `ENTER`. You'll have to type your password at this point. Next, type `sudo /etc/init.d/udev restart` and hit `ENTER` again to allow the changes to take effect.