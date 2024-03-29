# ARCGIS_Map_Copy
**Please note: This project has only been tested on Linux Mint 21.3 and Windows 11.**
## Prerequisites
Before you begin, ensure you have met the following requirements:
* On **Windows 11** machine, make sure you have `python` version ranging from 3.9.x to 3.11.x installed.
   * Open `Windows Powershell` and type `pip install arcgis`
* On **Linux 21.3** or similar distros, make sure the following packages are installed:
    * `python3` version ranging from 3.9.x to 3.11.x
    * `python3-pip`
    * `libkrb5-dev`
    * You can install them using the following command:
    ```bash
    sudo apt-get install python3 python3-pip libkrb5-dev
    ```
    * Then, install the required Python package
    ```bash
    python3 -m pip install arcgis
    ```

\
You can get the script by ```git clone https://github.com/KPCOFGS/ARC_GIS_Map_Copy.git```
## Usage
Make sure you have credentials for both source and destination accounts
\
\
Then, go to the folder where you cloned this repo and right click the folder and open in terminal, and type `python copy_map.py` or `python3 copy_map.py` to activate the script.
\
\
To get the map ID, first log into your ArcGIS Online account. Find and click ```Content``` tab. Then click on the map you want to copy, and then click ```view details```.\
![alt text](https://github.com/KPCOFGS/ARC_GIS_Map_Copy/blob/main/Screenshot%20from%202024-03-12%2010-43-31.png?raw=true)
\
On the right hand side, under ```Details``` section, There is the ```ID```. If you do not see ```Details``` section, you may want to scroll down a bit.\
![alt text](https://github.com/KPCOFGS/ARC_GIS_Map_Copy/blob/main/Screenshot%20from%202024-03-12%2010-45-42.png?raw=true)

