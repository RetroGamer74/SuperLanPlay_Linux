# SuperLanPlay Linux
Super Lan Play Linux Client (Tested on Ubuntu 16.04. It should work in others)

Welcome to Super Lan Play client for Linux.

# GUI Release

This program mainly requires graphic capabilities, so in this section will cover installation and run of the graphic version.

First you have to install a couple libraries. Just run this command.

``` 
sudo apt install libpcap0.8-dev libuv1-dev
``` 

When installation finished, you can download Super Lan Play client from this link:

https://www.dropbox.com/s/beg5ae0q3ny45e1/superlanplay.tar.gz?dl=0

![Download](Download.png?raw=true "Download")

Then you will see a popup like this. Use the default option to allow you to extract the file once finished. Take care you will have to do double click in the window when you go to extract it, so don't go so fast.

![Default Open](DownloadingFromBrowser.png?raw=true "Default Open")

Then click OK and wait for Download finished.

Then a new window will be shown.

![Default Extraction](ExtractNote.png?raw=true "Default Extraction")

If you see only one file named superlanplay.tar then double click on it to see what you see in next image.

![Default Extraction](ExtractRight.png?raw=true "Default Extraction")

When you see those 3 items it means you're ready to go. Click on the top left button, Extract. 

![Create Folder Extraction](CreateFolderForExtraction.png?raw=true "Create Folder Extraction")

And now create a folder to extract the files. You can create it doing click on the top right folder button. I created one named SLP. (SuperLanPlay) in my own user directory which is the default folder shown.

![Extraction](Extracted.png?raw=true "Extraction")


When you're ready to go, click on the bottom right button to extract the files in the SLP folder you've created.

LAST STEPS
==========

Once you've extracted open a terminal and run the command:

```
cd /home/$USER/SLP
```
![Change Directory](Directory.png?raw=true "Change Directory")

Finally run the program as root using sudo command. This is required because the library needs root permissions. And run the program that fit your needs, for example, if you need 32 bits version run superlanplay.x86 and if you want 64 bits version run superlanplay.x86_64.

``` 
sudo ./superlanplay.x86_64
```

![Run](Run.png?raw=true "Run")


# Command line Release

If you just want to run this as command line do the same steps in the GUI Release. When you reach the LAST STEPS title do this:

```
cd /home/$USER/SLP/superlanplay_Data/Resources
sudo  ./lan-play
```

It will ask you for a server/domain service. This is located in the settings of the Super Lan Play website which is located at:
http://lanboard.retrogamer.tech
Go to that URL and follow steps to register yourself. If you don't do this you won't get access because the service is firewalled.

# CREDITS

SuperLanPlay concept, web, and apps are developed by Team Retro.
lan-play concept and source code is developed by imspace, which you can locate it here:
https://github.com/spacemeowx2/switch-lan-play

