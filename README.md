# qgc building

## Download qgc source code
```
git clone --recursive https://github.com/mavlink/qgroundcontrol.git
git submodule init
git submodule update
```

## Install Qt

to install all nessesary Qt libraries and surroundings
```
sudo apt-get install qt5-default
```
Download the Qt installer https://www.qt.io/download-open-source/ .
Set the downloaded file to executable using
```
chmod +x
```
run the executable file
install Qt version 5.5.1

Install additional packages:
```
sudo apt-get install espeak libespeak-dev libudev-dev libsdl2-dev
```

Launch Qt Creator
Open qgroundcontrol.pro project
select kit: 
Desktop Qt 5.5.1 GCC bit
Configure project and build it.
