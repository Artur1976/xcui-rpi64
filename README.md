Install xcui on Raspberry Pi 3/4.

How do I install?

update your ubuntu first, then install panel

    sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install python2 software-properties-common libxslt1-dev libcurl3 libgeoip-dev python -y;
    wget https://github.com/Artur1976/xcui-rpi64/raw/main/install.py
    sudo python install.py

If you want to install main server with admin panel, choose MAIN.
If you want to install load balance on additional servers, add a server to panel in manage servers page, then run script and proceed with LB option.
