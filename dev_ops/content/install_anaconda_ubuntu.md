# Installing Anaconda on Linux (Ubuntu)

## relevant for versions  
anaconda version 2020.07


## Quick Install  

### direct link to installer:
[64-Bit (x86) Installer (550 MB)](https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh)

### go-there-yourself:

- browse to [anaconda.com/products/individual](https://www.anaconda.com/products/individual),  
- scroll down to "Anaconda Installers",  
- choose "64-Bit (x86) Installer (550 MB)"  


## Detailed Install  
open terminal  

enter  

    bash ~/Downloads/Anaconda3-2020.07-Linux-x86_64.sh  



## Configuration  

### to add a menu item for anaconda navigator:
open terminal  
`cd .local/share/applications  `

`touch anaconda-navigator.desktop  `

open files, go to .local/share/applications (if needed, enable "show hidden files")

open file anaconda-na

    vigator.desktop and add the following. (Replace |your user name| with your actual ubuntu user name.

[Desktop Entry]  
    Version=1.0  
Type=Application  
Name=Anaconda  
GenericName=Anaconda Navigator  
Exec=bash -c 'export PATH="/home/|your user name|/anaconda3/bin:$PATH" && /home/|your user name|/anaconda3/bin/anaconda-navigator'  
Comment=Scientific Python Development Environment - Python3
Icon=/home/|your user name|/anaconda3/lib/python3.8/site-packages/anaconda_navigator/static/images/anaconda-icon-256x256.png  
Terminal=false  
StartupNotify=true  
MimeType=text/x-python;  
Categories=Development;Science;IDE;Qt;Education;  





## previous versions

