#Installation of Ubuntu 15.04 on Windows 8.1
------------------------------
##Preparation
* Download Ubuntu
* Dowoland and install *win32DiskImager*
* Write the .iso file into USB flash disk with *win32DiskImager*
* Partition the disk on Windows: "Start" --> "Computer Manamgement" --> "Disk Manamgement" 

##Installation

* See https://www.youtube.com/watch?v=A0z0olUImac

##Starting Windows from Ubuntu
* Start the computer and press *Enter* 
* Press *F12* and choose the startup device as "Windows Boot Manager" 



##Change fond size
* "System Settings" --> "Universal Access" --> "Seeing" --> "Large Text"

##Change fond color in terminal 
* Open the file .bashrc in your home directory
```
gedit .bashrc
```
* Uncomment the line 
```
force_color_prompt=yes
```
