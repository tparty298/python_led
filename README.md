# python_led
rpi_ws281x/python/examples $ sudo python test.py
can work


git clone https://github.com/jgarff/rpi_ws281x
cd rpi_ws281x/python


cd
mkdir wifi-firmware
cd wifi-firmware
wget https://github.com/RPi-Distro/firmware-nonfree/raw/master/brcm/brcmfmac43430-sdio.bin
wget https://github.com/RPi-Distro/firmware-nonfree/raw/master/brcm/brcmfmac43430-sdio.txt
sudo cp *sdio* /lib/firmware/brcm/
sudo reboot
