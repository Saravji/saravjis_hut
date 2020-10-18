# Installing Anaconda on MacOS X  

## Relevant For Version  

- anaconda version 2020.07
- MacOS X Catalina (10.15.7) - should work similarily on older versions.

## Quick Install  

### direct link to installer:  

[64-Bit Graphical Installer (462 MB)](https://repo.anaconda.com/archive/Anaconda3-2020.07-MacOSX-x86_64.pkg)

### go-there-yourself:

- browse to [anaconda.com/products/individual](https://www.anaconda.com/products/individual),  

![alt text](images/anaconda_macosx_2020_07_01.png "Anaconda webpage")

- scroll down to "Anaconda Installers",  

![alt text](images/anaconda_macosx_2020_07_02.png "Anaconda webpage scrolled")

- choose "64-Bit (x86) Installer (550 MB)"  

![alt text](images/anaconda_macosx_2020_07_03.png "Anaconda download")


## Detailed Install  

- find the downloaded pkg in folder "Downloads"

![alt text](images/anaconda_macosx_2020_07_04.png "Downloads Folder")

- double-click it, The Anaconda Graphical Installer opens

![alt text](images/anaconda_macosx_2020_07_05.png "Anaconda Graphical Installer")

- click [continue] to run the test

![alt text](images/anaconda_macosx_2020_07_06.png "Anaconda Graphical Installer - Introduction")

- click [Continue] at Introduction screen

![alt text](images/anaconda_macosx_2020_07_07.png "Anaconda Graphical Installer - Read Me")

- click [Continue] at Read Me screen

![alt text](images/anaconda_macosx_2020_07_08.png "Anaconda Graphical Installer - License")

- click [Continue] at License screen

![alt text](images/anaconda_macosx_2020_07_09.png "Anaconda Graphical Installer - License Pop up")

- click [Agree] at License screen Pop-up

![alt text](images/anaconda_macosx_2020_07_10.png "Anaconda Graphical Installer - Destination Select")

**Note:** If you get the error message "You cannot install Anaconda3 in this location...." Select "Install for me only" again.

![alt text](images/anaconda_macosx_2020_07_11.png "Anaconda Graphical Installer - Destination Select")

- click [Continue] at Destination Select screen

![alt text](images/anaconda_macosx_2020_07_12.png "Anaconda Graphical Installer - Installation Type")

- click [Continue] at Installation Type screen

![alt text](images/anaconda_macosx_2020_07_13.png "Anaconda Graphical Installer - Installation running")

If you get a pop-up asking for Installer to get access to files in Download folder, click [OK] to allow

![alt text](images/anaconda_macosx_2020_07_14.png "Anaconda Graphical Installer - Installer allow access")

- click [Continue] at PyCharm IDE screen

![alt text](images/anaconda_macosx_2020_07_15.png "Anaconda Graphical Installer - PyCharm IDE")

- click [Close] at Summary screen

![alt text](images/anaconda_macosx_2020_07_16.png "Anaconda Graphical Installer - Summary")

- click [Move to Trash] at Move Installer to Trash pop-up

![alt text](images/anaconda_macosx_2020_07_17.png "Anaconda Graphical Installer - Move to Trash pop-up")


## Configuration  

to verify the installation, open a terminal (if you had one open during install, close and re-open).

if the prompt line starts with (base), the conda installation worked.  


```
    python --version
```  

should yield you a result as should  

```
    conda --version
```  

![alt text](images/anaconda_macosx_2020_07_18.png "Anaconda installation successfull")  

further, you should have "Anaconda-Navigator" in your launchpad:  

![alt text](images/anaconda_macosx_2020_07_19.png "Launchpad")  


## Version History

once updates to this page are made, the old versions are going to be archived here.  
